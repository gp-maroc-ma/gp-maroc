---

########################### hero slider ############################
hero_slider:
  enable : true
  slider_item:
    # slider item
    - subtitle : "We are here to"
      title : "Planning Business"
      content : "GPM Holding installs and maintains photovoltaic solar panels within the country of Morocco. Our 
      photovoltaic panels provide renewable energy that is environmentally friendly."
      bg_image_webp : "images/slider/01.jpg"
      bg_image : "images/slider/01.jpg"
      animation : "fadeInUp" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "#contacts"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/
        
    # slider item
    - subtitle : "We are here to"
      title : "Planning Business"
      content : "GPM Holding installs and maintains photovoltaic solar panels within the country of Morocco. Our 
      photovoltaic panels provide renewable energy that is environmentally friendly."
      bg_image_webp : "images/slider/02.jpg"
      bg_image : "images/slider/02.jpg"
      animation : "fadeInDown" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "#contacts"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/
        
    # slider item
    - subtitle : "We are here to"
      title : "Planning Business"
      content : "GPM Holding installs and maintains photovoltaic solar panels within the country of Morocco. Our 
      photovoltaic panels provide renewable energy that is environmentally friendly."
      bg_image_webp : "images/slider/03.jpg"
      bg_image : "images/slider/03.jpg"
      animation : "fadeInLeft" # animation select from : https://daneden.github.io/animate.css/
      button:
        enable : true
        label : "more details"
        link : "#contacts"
        animation : "zoomIn" # animation select from : https://daneden.github.io/animate.css/
        

################################## banner feature ############################
banner_feature:
  enable : true
  # Max use 4 item
  feature_item:
    # banner feature item loop
    - name : "Slim module design"
      icon : "far fa-gem" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Lorem ipsum dolor sit amet constur adipelit sed."
      
    # banner feature item loop
    - name : "High efficiency"
      icon : "far fa-chart-bar" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Lorem ipsum dolor sit amet constur adipelit sed."
      
    # banner feature item loop
    - name : "Eco-Friendly"
      icon : "far fa-lightbulb" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Lorem ipsum dolor sit amet constur adipelit sed."
      
    # banner feature item loop
    - name : "Reduce Shipping Cost"
      icon : "fas fa-tachometer-alt" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Lorem ipsum dolor sit amet constur adipelit sed."


################################## about ####################################
about:
  enable : true
  subtitle : "About Us"
  title : "We Are Dynamic Team and Solar Panels Business"
  content : "GPM Holding is a pioneering venture at the forefront of sustainable energy solutions. Specializing in the 
  production and installation of solar panels, we are committed to revolutionizing the renewable energy sector in 
  Africa. <br><br>Our focus extends beyond manufacturing to the development of PV plants, with one successful project 
  already   operational and several others in the development phase progressing steadily. These projects showcase our 
  dedication   to empowering communities with clean energy solutions. <br><br>In tandem with our manufacturing and 
  project development   endeavors, our service company delivers tailored solutions to meet the needs of both our valued 
  clients and our own internal operations. From installation and maintenance to technical assistance, the services GPM 
  provides ensure seamless functionality and unmatched customer satisfaction. <br><br>With a mission to harness the 
  power of the sun for a brighter tomorrow, GreenPower Morocco is shaping the future of energy production while 
  aligning itself with the Kingdom’s renewable energy goals."
  bg_image : "images/backgrounds/about-us-bg.jpg"
  bg_image_webp : "images/backgrounds/about-us-bg.jpg"
  image_webp : "images/about/about-us.jpg"
  image : "images/about/about-us.jpg"
  button:
    enable : true;
    label : "more service"
    link : "service/"

################################## funfacts ###############################
funfacts :
  enable : true
  funfacts_item :
    # fanfacts item loop
    - name : "project done"
      count : "50"
      icon : "fas fa-bullseye" # font-awesome 5 : https://fontawesome.com/icons/
      
    # fanfacts item loop
    - name : "Years Experience"
      count : "25"
      icon : "far fa-calendar-alt" # font-awesome 5 : https://fontawesome.com/icons/
      
    # fanfacts item loop
    - name : "Awards Win"
      count : "250"
      icon : "fas fa-award" # font-awesome 5 : https://fontawesome.com/icons/
      
    # fanfacts item loop
    - name : "Happy Coustomers"
      count : "500"
      icon : "far fa-smile" # font-awesome 5 : https://fontawesome.com/icons/


################################# feature ############################################
feature:
  enable : true
  subtitle : "Why Choose Us"
  title : "Why They Choose Bexar"
  image_webp : "images/feature/feature.webp"
  image : "images/feature/feature.jpg"
  content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eius tempor incididunt ut labore."
  feature_item:
    # feature item loop
    - name : "Creative Design"
      icon : "far fa-snowflake" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Excepteur sint occaecat cupidatat non proident sunt in culpa qui officia."
      
    # feature item loop
    - name : "Pixel Perfect Coding"
      icon : "fas fa-code" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Excepteur sint occaecat cupidatat non proident sunt in culpa qui officia."

################################# service ############################################
service:
  enable : true
  section: "service"
  show_item : 3
  # service item comes from "content/*/service" folder

################################# team ##############################################
team:
  enable : true
  section: "team"
  show_item : 3
  # team member comes from "content/*/team" folder

################################# project ############################################
project:
  enable : true
  section: "project"
  show_item : 4
  button:
    enable : true
    label : "more projects"
    link : "project/"
  # project item comes from "content/*/project" folder

################################# testimonial #########################################
testimonial:
  enable : true
  subtitle : "Testimonials"
  title : "What Clients Are Say?"
  testimonial_item:
    # testimonial item loop
    - client_image : "images/testimonial/client-1.jpg"
      name : "Dominic Allen"
      designation : "Designer"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit sed eiusmod tempor incididunt ut labore dolore magna aliqua.enim ad minim veniam.quis nostrud exercitation ullamco laboris nis aliquip ex ea commodo consequat. duis aute irure dolor in reprehen."
      
    # testimonial item loop
    - client_image : "images/testimonial/client-2.jpg"
      name : "Alex Pitt"
      designation : "Designer"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit sed eiusmod tempor incididunt ut labore dolore magna aliqua.enim ad minim veniam.quis nostrud exercitation ullamco laboris nis aliquip ex ea commodo consequat. duis aute irure dolor in reprehen."

    # testimonial item loop
    - client_image : "images/testimonial/client-3.jpg"
      name : "John Doe"
      designation : "Designer"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit sed eiusmod tempor incididunt ut labore dolore magna aliqua.enim ad minim veniam.quis nostrud exercitation ullamco laboris nis aliquip ex ea commodo consequat. duis aute irure dolor in reprehen."


################################# blog ################################################
cta:
  enable : true
  title : "Bexar give the smart solution for your business"
  bg_image_webp : "images/backgrounds/cta-lg.webp"
  bg_image : "images/backgrounds/cta-lg.jpg"
  button:
    enable : true
    label : "get a quote"
    link : "contact/"

################################# blog ################################################
blog:
  enable : true
  section : "blog"
  show_item : 3
  # blog post comes from "content/*/blog" folder

---
