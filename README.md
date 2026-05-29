# 🍎 Apple House + 📝 Todo App - Multi-App Hub

A combined project featuring an interactive 3D store and a modern todo list application, both built with Next.js and React.

## 🎯 Features

### 🍎 3D Apple Store
- Interactive 3D visualization with Three.js
- Orbit controls for navigation
- Realistic lighting and materials
- Shelves with randomly placed products
- Smooth animations

### 📝 Todo App
- ✅ Add, edit & delete tasks
- 💾 Local storage persistence
- 🎯 Filter tasks (All/Active/Completed)
- ✔️ Mark tasks complete
- 🗑️ Delete tasks
- 🧹 Clear completed tasks
- 📱 Fully responsive design
- ⌨️ Keyboard support (Enter to add)

## 🚀 Quick Start

### Prerequisites
- Node.js 16+
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/2501097-commits/apple-house-3d.git
cd apple-house-3d
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open your browser:
- 🏠 Home: http://localhost:3000
- 🍎 3D Store: http://localhost:3000 (main page)
- 📝 Todo App: http://localhost:3000/todo

## 📁 Project Structure

```
apple-house-3d/
├── app/
│   ├── page.tsx              # Home/Navigation page
│   ├── layout.tsx            # Root layout
│   ├── globals.css           # Global styles
│   └── todo/
│       └── page.tsx          # Todo app page
├── public/
│   ├── models/               # 3D models (.glb files)
│   └── textures/             # Texture images
├── package.json
├── tsconfig.json
├── tailwind.config.js
├── postcss.config.js
├── next.config.js
└── README.md
```

## 🎮 Usage

### 3D Apple Store
- **Mouse Drag**: Rotate view
- **Scroll**: Zoom in/out
- **Right Click Drag**: Pan view
- Add your `.glb` models to `public/models/`
- Add textures to `public/textures/`

### Todo App
1. Type your task and press Enter or click Add
2. Click circle to mark complete
3. Click trash to delete
4. Use tabs to filter tasks
5. Tasks auto-save to browser storage

## 🛠 Technologies

- **Next.js 14** - React framework
- **React 18** - UI library
- **Three.js** - 3D graphics
- **React Three Fiber** - 3D abstraction
- **Tailwind CSS** - Styling
- **Lucide Icons** - Icons
- **TypeScript** - Type safety
- **Local Storage** - Data persistence

## 📱 Responsive Design

Both applications are fully responsive:
- ✅ Mobile (320px+)
- ✅ Tablet (768px+)
- ✅ Desktop (1024px+)

## 🎨 Customization

### Change 3D Store
Edit `app/page.tsx`:
- Modify lighting
- Change camera position
- Add more shelves
- Customize colors

### Customize Todo App
Edit `app/todo/page.tsx`:
- Change theme colors
- Modify layout
- Add new features
- Adjust styling

## 📦 Adding 3D Models

1. Place `.glb` files in `public/models/`
2. Reference in code:
```tsx
const { scene } = useGLTF("/models/my-model.glb");
```

## 💾 Local Storage

- Todo tasks auto-save
- No backend required
- Persists across sessions
- Browser-based storage

## 🚀 Build & Deploy

### Production Build
```bash
npm run build
npm start
```

### Deploy to Vercel
```bash
npm install -g vercel
vercel
```

## 🔧 Troubleshooting

### 3D Models not showing?
- Check file paths in `public/models/`
- Verify `.glb` files are valid
- Check browser console for errors

### Todo not saving?
- Enable localStorage in browser
- Check browser console
- Clear cache and reload

### Performance issues?
- Reduce model complexity
- Optimize texture sizes
- Limit number of instances

## 🌟 Future Enhancements

- [ ] Task categories
- [ ] Due dates
- [ ] Dark mode
- [ ] Multiple todo lists
- [ ] AR preview for products
- [ ] Cloud sync
- [ ] User authentication
- [ ] Shopping cart
- [ ] Payment integration

## 📄 License

MIT License - Use freely for personal or commercial projects

## 🤝 Contributing

Feel free to fork and submit pull requests!

## 📚 Resources

- [Next.js Docs](https://nextjs.org/docs)
- [React Docs](https://react.dev)
- [Three.js Docs](https://threejs.org/docs)
- [Tailwind Docs](https://tailwindcss.com/docs)
- [React Three Fiber](https://docs.pmnd.rs/react-three-fiber/)

---

Made with ❤️ - Multi-app hub for creativity & productivity
