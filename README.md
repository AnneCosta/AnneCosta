<h2 align="center"> Hello, visitor! 👋👩‍💻 </h2>


```js
import Bio from '../Anne/Informations';

export function Anne() {
    const aboutMe = {
      name      : "Fabianne Costa",
      aka       : "Anne",
      pronouns  : [ "She", "Her" ] ,
      code      : [ "HTML", "CSS", "Javascript" ],
      techInfo  : 
      {
        front   : [ "Vue.js", "Nuxt.js", "Materialize", "Tailwind", "Bootstrap" ],
        back    : [ "Node.js", "Express" ],
      },
      database  : [ "MySQL" ],
      learning  : [ "React", "Python" ],
      challenge : "Learn about Python (Numpy/Pandas) and React (Next/Vite)"
    }
    
    return (
      <>
        <Bio info={aboutMe} />
      </>
    )
}

```
<div align="center">
    <a href="https://instagram.com/annes.io" target="_blank" rel="noopener noreferrer"> 
        <img src="https://img.icons8.com/bubbles/50/000000/instagram.png">
    </a> 
    <a href="https://www.linkedin.com/in/fabiannecosta/" target="_blank" rel="noopener noreferrer"> 
        <img src="https://img.icons8.com/bubbles/50/000000/linkedin.png">
    </a> 
</div>
