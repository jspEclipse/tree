<h1 align="center">🌲 Tree</h1>
<h3 align="center">Showcase your brand your way with our free open-source LinkTree. Customize fonts, images, templates, and analytics via a thriving plug-in ecosystem. .</h3>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/jspEclipse/tree?color=04D361&labelColor=000000">
  
  <a href="https://www.linkedin.com/in/johnggli/">
    <img alt="Made by" src="https://img.shields.io/static/v1?label=made%20by&message=Jsp%20Eclipse&color=04D361&labelColor=000000">
  </a>
  
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/jspEclipse/tree?color=04D361&labelColor=000000">
  
  <a href="https://github.com/jspEclipse/tree/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/jspEclipse/tree?color=04D361&labelColor=000000">
  </a>
</p>

<p align="center">
  <a href="#-about-the-project">About the project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-getting-started">Getting started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">License</a>
</p>

---

<p align="center">
  <img alt="screenshot" src="https://github.com/jspEclipse/tree/blob/main/tree/public/images/demo2.png">
</p>

---

## 💡 About the project

This is an open source project that serves as a free alternative to the Linktree website.
- [Demo](https://johnggli.github.io/linktree)

## 🚀 Getting started

## Features

- Profile picture component
- Name component  
- Bio component
- Link button component to add infinite external links  
- Fullscreen background image
- Responsive design

## Usage

The main App component composes together the visual components:

```jsx
function Home() {

  return (
    <div className="h-screen" style={{backgroundImage}}>
      <ProfilePic />
      <Name /> 
      <Bio />

      <div className="links">
        <LinkButton/> 
        <LinkButton/>  
      </div>
    </div>
  )
}
```

Simply modify the background, pass the relevant props to the above components, and add/configure LinkButton components to create your own LinkTree.

## Customizing

The background image and link buttons can be fully customized by modifying the appropriate assets and component props.

Component props:

- ProfilePic - src 
- Name - children
- Bio - children 
- LinkButton - link, linkName 

## Contributing

Pull requests are welcome to improve the components and add additional customization features. Please open an issue first to discuss proposed changes.

## License

MIT
