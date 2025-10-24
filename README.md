#  GemCart Frontend

React-based frontend for the GemCart luxury jewelry e-commerce platform.

##  Quick Start

```bash
npm install
npm start
```

**App URL**: http://localhost:3000

##  Features
1.  Product browsing with categories
2.  Shopping cart functionality
3.  User authentication
4.  M-Pesa checkout integration
5.  Mobile responsive design
6.  Featured collection showcase

##  Tech Stack
1. **React 18** - UI framework
2. **React Router** - Navigation
3. **Tailwind CSS** - Styling
4. **Context API** - State management

##  Project Structure
```
src/
├── components/         # Reusable components
│   ├── ProductCard.jsx
│   ├── Footer.jsx
│   └── FeaturedCollection.jsx
├── pages/             # Page components
│   ├── Home.jsx
│   ├── Products.jsx
│   ├── Cart.jsx
│   └── Checkout.jsx
├── context/           # React context
│   ├── AuthContext.jsx
│   └── CartContext.jsx
└── App.jsx           # Main app component
```

## 🔧 Environment Variables
```bash
REACT_APP_API_URL=http://localhost:5000
REACT_APP_ENVIRONMENT=development
```

##  Testing
```bash
npm test
```

##  Deployment
1. **Netlify**: Connect GitHub repo
2. **Vercel**: `vercel --prod`
3. **Build**: `npm run build`


##  Test Account
1. **Email**: seller@gemcart.com
2. **Password**: password