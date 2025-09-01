# 🚀 Free Deployment Guide for Render.com

## ✅ Prerequisites (Already Done!)
- ✓ Production build working
- ✓ render.yaml configuration created
- ✓ Environment variables documented

## 📋 Step-by-Step Deployment

### 1. Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and create a new repository
2. Make it **public** (required for free tier)
3. Copy your Replit code to the new repository

### 2. Sign Up for Render
1. Go to [render.com](https://render.com)
2. Click "Get Started for Free"
3. Sign up with your GitHub account
4. This automatically connects your repositories

### 3. Deploy Your App
1. Click "New +" → "Blueprint"
2. Connect your GitHub repository
3. Render will automatically detect the `render.yaml` file
4. Click "Apply" to start deployment

### 4. Set Environment Variables
In the Render dashboard, add these environment variables:

**Required Variables:**
- `OPENAI_API_KEY`: `sk-...` (your OpenAI key)
- `STRIPE_SECRET_KEY`: `sk_test_...` (your Stripe secret)
- `VITE_STRIPE_PUBLIC_KEY`: `pk_test_...` (your Stripe public key)

**Auto-configured by Render:**
- ✓ `DATABASE_URL` (PostgreSQL connection)
- ✓ `SESSION_SECRET` (auto-generated)
- ✓ `NODE_ENV` (set to production)
- ✓ `PORT` (set to 10000)

### 5. Wait for Deployment
- Database creation: ~2 minutes
- App deployment: ~5 minutes
- First build might take longer

### 6. Access Your Live App
- Your app will be available at: `https://your-app-name.onrender.com`
- Database will be automatically connected
- SSL certificate is included for free

## 🎯 What You Get FREE:
- ✅ 750 hours/month runtime (31+ days)
- ✅ PostgreSQL database (500MB)
- ✅ SSL certificate
- ✅ Custom domain support
- ✅ Automatic deployments from GitHub
- ✅ Build logs and monitoring

## 🔄 Future Updates
Every time you push to GitHub:
- Render automatically rebuilds and deploys
- Zero downtime deployments
- Rollback capability if needed

## 🆘 Troubleshooting
- **Build fails**: Check the build logs in Render dashboard
- **App crashes**: Verify all environment variables are set
- **Database issues**: Database URL is auto-generated, don't modify it

## 📱 Your Live App Features
Once deployed, your app will have:
- AI prompt generation with OpenAI
- Stripe subscription payments
- User authentication
- PostgreSQL database
- Responsive design
- Professional SSL certificate

**Ready to deploy? Let's get your app live! 🚀**