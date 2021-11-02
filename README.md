<section>
<h1 class="line-1 anim-typewriter">Sunnyside agency landing page challenge hub</h1>



<img class="img__project " src="screen.gif">

<div class="links">
    <a href="#the_challenge">The challenge</a> |
     <a href="#links">Links</a> |
      <a href="#built_with">Built with</a> |
       <a href="#what_i_learned">What I learned</a> |
       <a href="#resources">Resources</a> |
       <a href="#author">Author</a> 
</div>

<h2 id="the_challenge"> 🌋 The challenge</h2>
<hr>

- Your challenge is to build out this landing page and get it looking as close to the design as possible.
- Your users should be able to:

  - View the optimal layout for the site depending on their device's screen size
  - See hover states for all interactive elements on the page



<h2 id="links">🔗 Links</h2>
<hr>

- Solution URL: []()
- Live Site URL: []()


<h2 id="built_with">👷‍♂️ Built with</h2>
<hr>

-  <img class="icon" src="https://img.icons8.com/color/20/000000/javascript--v2.png"/> JavaScript
-  <img class="icon" src="https://img.icons8.com/color/20/000000/sass-avatar.png"/> Sass
-  <img class="icon" src="https://img.icons8.com/color/20/000000/html-5--v1.png"/> HTML



<h2 id="what_i_learned">👨‍🎓 What I learned</h2>
<hr>

- In it I learned how to create a hamburger menu




<h2 id="resources">📚 Resources</h2>
<hr>

- [how to create a menu burguer](https://piccalil.li/tutorial/build-a-fully-responsive-progressively-enhanced-burger-menu/)


<h2 id="author">😬 Author</h2>
<hr>

- Frontend Mentor - [@MarlonPassos-git](https://www.frontendmentor.io/profile/MarlonPassos-git)
  
  </section>

<style>

    section {
        scroll-behavior: smooth;
    }
    .icon {
        transform: translateY(3px);
        width: 20px;
        height: 20px;                    
    }

    
    .links {
        display: flex;
        justify-content: center;
        gap: 10px;
        margin-botoom: 30px;
    }
    
    a {
        cursor: pointer;
        : none;
    }

    .img__project {
        width: 800px;

    }

   .line-1{
    position: relative;
    top: 50%;  
    width: 100%;
    margin: 0 auto;
    font-size: 180%;
    text-align: center;
    white-space: nowrap;
    overflow: hidden;
    transform: translateY(-50%);    
}

/* Animation */
.anim-typewriter{
  animation: typewriter 4s steps(44) 1s 1 normal both
}
@keyframes typewriter{
  from{width: 0;}
  to{width: 24em;}
}


</style>