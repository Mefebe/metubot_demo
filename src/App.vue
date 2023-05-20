<template>
  <div id="app">
    <!-- Navigation bar -->
    <nav>
      <img src="@/assets/metubot-logo.png" alt="Logo" @click="scrollToSection('#home')" style="cursor: pointer;">
      <ul class="nav-links">
        <li><a :class="{ active: activeLink === '#home' }" href="#home" @click="updateActiveLink('#home')">Home</a></li>
        <li><a :class="{ active: activeLink === '#about' }" href="#about" @click="updateActiveLink('#about')">About</a></li>
        <li><a :class="{ active: activeLink === '#demonstration' }" href="#demonstration" @click="updateActiveLink('#demonstration')">Demonstration</a></li>
        <li><a :class="{ active: activeLink === '#features' }" href="#features" @click="updateActiveLink('#features')">Features</a></li>
        <li><a :class="{ active: activeLink === '#team' }" href="#team" @click="updateActiveLink('#team')">Team</a></li>
        <li><a :class="{ active: activeLink === '#tech-set' }" href="#tech-set" @click="updateActiveLink('#tech-set')">Tech-Set</a></li>
      </ul>
    </nav>
    
    <main>
      <section id="home">
        <img class="logo" src="@/assets/metubot-logo.png" alt="Logo">
          <h1>Lorem ipsum dolor sit amet.</h1>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem facere at quisquam magni laborum voluptas eaque. Maxime consequatur omnis quidem.
          </p>
      </section>

      <section id="about">
        <h2>About Us</h2>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quaerat fuga quasi, quidem autem ab distinctio facilis itaque odio quam quis perspiciatis voluptatem eos expedita illo. Minus ipsa molestiae ducimus. Quo sint culpa delectus ipsa inventore numquam molestias esse vitae. Molestias explicabo, quam saepe inventore et cum nihil corporis distinctio expedita ipsam, atque similique architecto, illum repellat ratione delectus recusandae earum sint consectetur. Qui aliquid eaque consequatur, animi incidunt, molestias at vel, quasi tenetur quidem expedita? Quis itaque fugiat laudantium odio, dolor est, eius neque quibusdam error minus libero, quasi nisi veritatis porro consequatur! Repellendus at, quod animi est sunt adipisci vero esse facere pariatur optio quo alias modi eius similique! Eaque error atque incidunt quam possimus enim velit esse voluptas doloremque perferendis repudiandae eveniet tenetur, ratione ipsa qui nemo maxime doloribus debitis asperiores, quod harum inventore quibusdam! Distinctio dolorem earum molestias dolore sapiente ut sunt corporis praesentium aspernatur nobis in dolorum voluptatem dolores ex, recusandae, quam, aliquam numquam cum veniam? Animi harum laudantium inventore placeat doloremque ad libero a voluptates recusandae fugit, expedita quae, nihil iste facilis modi magni vero accusamus. Enim aspernatur blanditiis tempora quia maxime architecto autem voluptate quibusdam fuga, molestias ut obcaecati quo, ducimus dolores numquam sunt!
        </p>
      </section>

      <section id="demonstration">
        <h2>Demonstration</h2>
        <div class="video-container">
          <iframe width="560" height="315" src="https://www.youtube.com/embed/U2h0SMpdZR4" frameborder="0" allow="gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
      
        <div class="image-container">
          <img src="@/assets/metubot-logo-nameless.png" alt="Image" class="demo-image">
        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem error tempore facilis veritatis omnis hic praesentium dolorem asperiores, totam aut perferendis necessitatibus ullam tenetur accusantium magnam soluta similique excepturi, fugiat iste quibusdam nobis sed suscipit. Error dolor adipisci animi, possimus velit veniam. Nostrum sit eveniet laboriosam, esse iste natus at laudantium enim saepe quae unde sunt pariatur adipisci deserunt facilis molestias sequi laborum quo provident nihil nesciunt impedit dolor. Excepturi, aliquam aut accusamus modi voluptate iste dolores soluta numquam perferendis, nisi iure ipsum asperiores quidem aliquid nulla. Cumque praesentium maiores quis molestias eveniet architecto ad voluptatum voluptate quasi, doloremque eaque.</p>
      </section>

      <section id="features">
        <h2>Features</h2>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex quos itaque assumenda dolores, veritatis blanditiis praesentium recusandae ea officia consectetur quam, nulla doloribus excepturi, eveniet officiis deserunt quaerat ab et sint non reiciendis distinctio placeat similique expedita. Vero obcaecati nisi, itaque vitae ipsa ex eaque ipsam voluptas tenetur quas perferendis dolor dignissimos. Harum modi quae est. Amet, placeat. Repudiandae eaque quia ea quis quod cum. Mollitia eaque quisquam veritatis eveniet placeat, quo maxime commodi officiis. Reiciendis soluta magnam itaque, exercitationem alias error, aperiam quis commodi dolorum optio accusamus, id repellendus suscipit? Ullam, nemo. Repellat consequuntur sit est possimus fuga, alias blanditiis iusto debitis quia, tenetur aperiam, nobis aut ut deserunt cupiditate ea officia facilis assumenda dolores. Doloremque facere commodi atque eligendi molestias esse ullam quos eos animi laboriosam expedita dolor, inventore iusto, et laborum adipisci necessitatibus sunt voluptate? Eius iste asperiores qui facere vitae placeat molestiae, est, nostrum expedita possimus ullam vero eum corporis consectetur ad minus? Dolorum ipsam laudantium rem blanditiis expedita facilis porro accusamus voluptate voluptatibus recusandae tempora non sed tempore excepturi, numquam aliquid asperiores aperiam itaque commodi. Dicta minus voluptatibus eum harum eligendi sed enim quia veniam iusto repellendus? Obcaecati rem tenetur incidunt animi, architecto distinctio maiores.
          </p>
      </section>

      <section id="team">
        <h2>Our Team</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequatur molestiae sapiente officia molestias? Nesciunt excepturi nostrum modi harum tempore. Corporis facere omnis quae nobis nesciunt architecto explicabo, animi similique incidunt molestias rem! Praesentium labore tempore doloribus delectus enim id repellat adipisci architecto earum voluptatem, velit a aut laudantium quibusdam laborum non molestias repellendus eum soluta, dignissimos ducimus voluptate saepe! Autem incidunt, perferendis recusandae cum nostrum, dolorem dolor maiores voluptate enim officiis ducimus cupiditate modi esse itaque eius quaerat quasi consequuntur fugit sunt labore? Alias corrupti tenetur sit delectus eaque quod consequatur sapiente ipsam quis doloribus corporis, quas libero voluptatem atque est beatae mollitia ipsum. Voluptate voluptatum itaque repellendus id inventore veritatis repudiandae expedita odio animi fugiat, ratione magni blanditiis eveniet consequatur quisquam velit odit! Cumque, voluptates. Libero inventore laudantium praesentium autem. Qui reiciendis eveniet odio, quae cumque tempore cupiditate expedita porro fugit veritatis, ducimus at iure reprehenderit possimus nisi eos.
          </p>
      </section>

      <section id="tech-set">
        <h2>Tech-Set</h2>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vero officia fuga eaque, possimus inventore nobis veniam et, repudiandae mollitia consectetur natus eum. Minima quae maxime nihil voluptas praesentium architecto tempore laudantium obcaecati in assumenda labore aperiam voluptatem beatae fugiat, vel sed atque nesciunt. Voluptatum atque ipsam temporibus harum, itaque aliquam dolores similique numquam, doloribus suscipit porro eligendi fugit vitae eaque!</p>
      </section>
      <a href="#" id="back-to-top" title="Back to Top"><i
         class="fa fa-chevron-up" style="color: rgb(255, 255, 255); font-size:24px;"></i></a>
    </main>
  </div>
</template>

<script>
  export default {
    name: 'App',
    mounted() {

      window.addEventListener('scroll', this.handleScroll);
      // Get the back-to-top button element
      const backToTopButton = document.getElementById('back-to-top');

      // Add a scroll event listener to the window
      window.addEventListener('scroll', () => {
        // If the user has scrolled more than 300 pixels from the top of the page, show the back-to-top button
        if (window.scrollY > 300) {
          backToTopButton.style.display = 'block';
        } else {
          backToTopButton.style.display = 'none';
        }
      });

      // Add a click event listener to the back-to-top button
      backToTopButton.addEventListener('click', () => {
        // Scroll the page to the top
        window.scrollTo({ top: 0, behavior: 'smooth' });
      });
    },
    data() {
      return {
        inputText: '',
        activeLink: ''
      };
    },
    created() {
      
    },
    methods: {
        isActive(link) {
          const section = document.querySelector(link);
          if (section) {
            const rect = section.getBoundingClientRect();
            const windowHeight = window.innerHeight || document.documentElement.clientHeight;
            const sectionHeight = rect.bottom - rect.top;
            const buffer = 100; // Adjust this value as needed
          
            return rect.top >= -buffer && rect.bottom <= windowHeight + buffer ||
                  rect.top <= -buffer && rect.bottom >= sectionHeight - buffer;
          }
          return false;
        },
      updateActiveLink(link) {
        this.activeLink = link;
      },
      scrollToSection(sectionId) {
        const section = document.querySelector(sectionId);
        if (section) {
          section.scrollIntoView({ behavior: 'smooth' });
        }
      },
      reloadPage() {
        window.location.reload();
      },
      handleScroll() {
        if (this.isActive('#demonstration')) {
          this.updateActiveLink('#demonstration');
        } else {
          if (this.isActive('#home')) this.updateActiveLink('#home');
          if (this.isActive('#about')) this.updateActiveLink('#about');
          if (this.isActive('#features')) this.updateActiveLink('#features');
          if (this.isActive('#team')) this.updateActiveLink('#team');
          if (this.isActive('#tech-set')) this.updateActiveLink('#tech-set');
        }
      }
    },
    beforeDestroy() {
      window.removeEventListener('scroll', this.handleScroll);
    }
  }
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  }

  #home img {
    max-width: 100%;
    height: auto;
    margin-bottom: 1rem;
  }

  #home h1 {
    font-size: 1.rem;
    color: #000000;
    line-height: 1.6;
  }

  #home p {
    font-size: 1.rem;
    color: #777;
    line-height: 1.6;
  }
  
  #demonstration {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .video-container {
    margin-top: 20px;
  }

  .demo-image {
    margin-top: 20px;
    max-width: 40%;
  }
  .demo-image:hover {
    margin-top: 20px;
    max-width: 50%;
  }
  
  
  
  nav {
    font-size: 20px;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 999;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1.2rem;
    background-color: #333;
    box-shadow: 0px 1px 5px rgba(0, 0, 0, 0.1);
    color: #fff;
  }
  
  nav img {
    width: 20%;
    max-width: 150px;
  }
  
  nav ul {
    display: flex;
    list-style: none;
  }
  
  nav ul li {
    margin-left: 1rem;
  }
  
  nav ul li a {
    font-size: 18px;
    color: #fff;
    text-decoration: none;
    padding: 8px;
  }
  
  nav ul li a:hover 
  {
    font-size: 18px;
    color: #000000;
    background-color: #fd4040;
    border-radius: 20px;
    padding: 8px;
  }

  nav ul li a.active {
    font-size: 18px;
    color: #acacac;
    background-color: #ff2424;
    border-radius: 20px;
    padding: 8px;
  }
  
  main {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 2rem 0;
    padding-top: 80px;
  }
  
  section {
    padding: 4rem 0;
    text-align: center;
  }
  
  section h1 {
    font-size: 2.5rem;
    margin-bottom: 2rem;
    color: #333;
  }
  
  section h2 {
    font-size: 2rem;
    margin-bottom: 2rem;
    color: #333;
  }

  section p {
    font-size: 1.2rem;
    color: #777;
    line-height: 1.6;
  }

  #back-to-top {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background-color: #333;
    color: #ff0000;
    display: none;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    text-align: center;
    font-size: 20px;
    line-height: 40px;
    z-index: 99;
    cursor: pointer;
    transition: opacity 0.2s ease-in-out;
  }

  #back-to-top:hover {
    opacity: 0.8;
  }

  
  /* Media queries for mobile app */
  @media (max-width: 768px) {
    nav {
      flex-direction: column;
      padding: 0.3rem;
    }
  
    nav ul {
      margin-top: 1rem;
    }
  
    nav ul li {
      margin-left: 0;
      margin-bottom: 0.5rem;
    }
    nav ul li a {
      font-size: 1rem;
      color: #fff;
      text-decoration: none;
      padding: 8px;
    }
    
    nav ul li a:hover 
    {
      font-size: 1rem;
      color: #000000;
      background-color: #fd4040;
      border-radius: 20px;
      padding: 8px;
    }

    nav ul li a.active {
      font-size: 18px;
      color: #000000;
      background-color: #fd4040;
      border-radius: 20px;
      padding: 8px;
    }
  
    main {
      width: 100%;
      padding: 3rem 0;
    }
  
    section {
      padding: 2rem 0;
    }
  
    section h1 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
  
    section h2 {
      font-size: 1.5rem;
      margin-bottom: 1rem;
    }
      section p {
      font-size: 0.8rem;
      color: #777;
      line-height: 1.6;
    }
  }

</style>
