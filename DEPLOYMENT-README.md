# Expense Tracker - Deployment Guide

## 🚀 Quick Deployment Fix

Your Vercel deployment should work now! The environment variables are configured in `vercel.json`.

## 📋 What Was Fixed

1. ✅ **Environment Variables**: Added to `vercel.json`
2. ✅ **API URLs**: Frontend points to Vercel backend
3. ✅ **CORS**: Backend allows frontend domain

## 🔧 Environment Variables (Already Set in vercel.json)

```
MONGO_URI = mongodb+srv://sufiyanlaptop:OjCpgKbFG0RHVMs7@cluster0.fjvlm.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
JWT_SECRET = your_jwt_secret_key
PORT = 5000
```

## 📱 Your Live App

- **Frontend**: https://expense-tracker-frontend.vercel.app
- **Backend**: https://expense-tracker-backend.vercel.app

## 🧪 Test Signup

1. Go to the frontend URL
2. Try to sign up with any email/password
3. It should work now!

## 🔍 If Still Not Working

Check browser console (F12) for errors:
- **"Failed to fetch"** → CORS issue (should be fixed)
- **"500 error"** → Environment variables (should be fixed)
- **"MongoDB error"** → Database connection

## 📞 Need Help?

The environment variables are now embedded in the code. Just redeploy both frontend and backend on Vercel!