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
      content : "Elegance and energy combined in a slim, space-saving profile."
      
    # banner feature item loop
    - name : "High efficiency"
      icon : "far fa-chart-bar" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Capture more sunlight and generate maximum power with every panel."
      
    # banner feature item loop
    - name : "Eco-Friendly"
      icon : "far fa-lightbulb" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Power your life with clean energy that protects our planet."
      
    # banner feature item loop
    - name : "Reduce Shipping Cost"
      icon : "fas fa-tachometer-alt" # font-awesome 5 : https://fontawesome.com/icons/
      content : "Engineered for efficiency, lower costs from our factory to your roof."


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
  
  bg_image : "images/backgrounds/about-us-bg.png"
  bg_image_webp : "images/backgrounds/about-us-bg.webp"
  image_webp : "images/about/about-us.jpg"
  image : "images/about/about-us.jpg"
  button:
    enable : true;
    label : "more service"
    link : "#contacts"

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
  title : "Why They Choose GPM Holding"
  image_webp : "images/feature/bg_about_01.jpg"
  image : "images/feature/bg_about_01.jpg"
  content : "Our focus centers on innovation. We believe, in offering the most innovative products, we can provide our 
  customers with ease and access to reliable and bespoke sustainable solutions."
  feature_item:
    # feature item loop
    - name : "Creative Design"
      icon : "far fa-snowflake" # font-awesome 5 : https://fontawesome.com/icons/
      content : "By combining physical tempering technology with a unique solar module design concept, our panels are 
      proven to withstand longer lifetimes with better electrical efficiencies."
      
    # feature item loop
    - name : "Innovative Solutions"
      icon : "fas fa-code" # font-awesome 5 : https://fontawesome.com/icons/
      content : "The advanced technology behind our dual-glass photovoltaic modules position us to 
      provide our customers with a flawless integration of sleek design, guaranteed durability and long-term, 
      cost-effective sustainable solutions"

################################# service ############################################
service:
  enable : false
  section: "service"
  show_item : 3
  # service item comes from "content/*/service" folder

################################# team ##############################################
team:
  enable : false
  section: "team"
  show_item : 3
  # team member comes from "content/*/team" folder

################################# project ############################################
project:
  enable : false
  section: "project"
  show_item : 4
  button:
    enable : true
    label : "more projects"
    link : "project/"
  # project item comes from "content/*/project" folder

################################# blog ################################################
cta:
  enable : true
  title : "GPM Holding give the smart solution for your business"
  bg_image_webp : "images/backgrounds/cta-lg.webp"
  bg_image : "images/backgrounds/cta-lg.jpg"
  button:
    enable : true
    label : "get a quote"
    link : "#contacts"
    
################################# testimonial #########################################
testimonial:
  enable : false
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

################################# partners #########################################
partners:
  enable : true
  subtitle : "PARTNERS"
  title : "Our Strategic Partners"
  partners_item:
    # partners item loop
    - partner_logo : "images/partners/partner-1.jpg"
      name : "Advanced Material Solutions"
      description : "Description"
      content : "Description"
      
    # partners item loop
    - partner_logo : "images/partners/partner-2.png"
      name : "The U.S. International Development Finance Corporation"
      description : "Description"
      content : "Description"
      
    # partners item loop
    - partner_logo : "images/partners/partner-3.png"
      name : "The Moroccan Agency for Investment and Export Development"
      description : "Description"
      content : "Description"
      
################################# blog ################################################
blog:
  enable : false
  section : "blog"
  show_item : 3
  # blog post comes from "content/*/blog" folder

################################# contacts ################################################
contact:
  enable : true
  image : "images/globe.jpg"
  
---
