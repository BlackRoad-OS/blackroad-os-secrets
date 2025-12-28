# Credentials Management

**Location:** `/credentials/`

---

## 📂 Directory Structure

```
credentials/
├── api-keys/           → API keys organized by service
├── ssh-keys/           → SSH keys for servers
└── certificates/       → SSL/TLS certificates
```

---

## 🔑 API Keys Management

### Storage Format

Each service has its own `.env` file:

```bash
# Example: credentials/api-keys/clerk.env
CLERK_SECRET_KEY=sk_test_...
CLERK_PUBLISHABLE_KEY=pk_test_...
```

### Services:

- **clerk.env** — Authentication (Clerk)
- **stripe.env** — Payments (Stripe)
- **mapbox.env** — Maps (Mapbox)
- **openai.env** — OpenAI API keys
- **anthropic.env** — Claude API keys
- **google-ai.env** — Gemini API keys
- **cloudflare.env** — Cloudflare API tokens
- **railway.env** — Railway deployment tokens
- **vercel.env** — Vercel deployment tokens
- **github.env** — GitHub API tokens

---

## 🔐 Security Best Practices

1. **Rotation Schedule:** Every 90 days
2. **Access Control:** Need-to-know basis only
3. **Never commit to public repos**
4. **Use environment variables in production**
5. **Separate keys for dev/staging/production**

---

## 📝 Usage

### Loading Keys in Applications:

```bash
# Load from this repo
source /Users/alexa/blackroad-os-secrets/credentials/api-keys/clerk.env

# Or copy to project .env (DO NOT COMMIT!)
cp credentials/api-keys/clerk.env ~/project/.env.local
```

### Adding New Keys:

```bash
# Create new service file
cat > credentials/api-keys/newservice.env <<EOF
SERVICE_API_KEY=your_key_here
SERVICE_SECRET=your_secret_here
EOF

# Commit securely
git add credentials/api-keys/newservice.env
git commit -m "Add: NewService API keys"
git push origin main
```

---

**Last Updated:** December 28, 2024
