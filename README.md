# Project-Plans


We want a schema 

something we can list out 

  schema: 
    - Name 
    - Img 
    - attributes/list items 
    - created at this point in time 
    - posted by (name) at (date in time)
    - marvel comics - comment section below 
    - ^ schema        ^schema 
    
    Controller Comment section:
        Schema: 
          username: String
          comment: String 
          date: String
          (notes on relating two models)
          
          ^^^ this will be our first stretch goal
          
            
    CRUD
    
    
    Controller Marvel Comics:
        Schema: 
          img:
          author:
          superhero:
          date released:
          
          
          ^^^ this will be our MVP 
    
    CRUD
    
    
    INSIDE REACT APP
    
    C  user should be able to add comments
    R  user should be able to read existing comments
    U user should be able to update existing comments
    D user should be able to delete existing comments
    
    
    to add comics 
    to update existing comcis 
    delete comics
    and see comics
    
    STRETCH GOAL 
    If we want to sort it by superhero name 
    
    display a bunch of heros 
    third party api (superheros)
    
    
    show more button, button is inside specific card for the comic, more information about the comics
    hide everything else and just show information about the one that we clicked. (axios.get('link/:id')
    render everything that is within that object. 
    
    Add a filter that is directing users by superhero-type. (spiderman, wolvering, ironman, etc.) list the comics associated with that state(state representing name of superhero).
    
    the comments could be inside of a container and implement a scroll-through (overflow) and implement in each of those individual divs an overflow incase the comments go long. 
    the width of each comment is the width of the container itself. 
    
    each divs would be stacked, and you'll be able to scroll through them, but also scroll through each one individually if it is lengthy. 
    
    
    WORK TO BE DONE:
    establish heroku - together 
    mongo atlas - together 
    init repo - together 
    react-app - together 
    back-end - together 
    
    WORK THAT CAN BE INDIVIDUAL:
    construct individual components
      - comment section 
        showing all the comments. 
      - comics(flexbox)
        - search by hero name
      - individual comic page(almost like a show page)
        - show comments for specific comic(show page)
      
      HOME PAGE
      displaying all comics 
      comment sections - stretch
    
    
    CONTROLLERS ======>
        One component for creating comics (create.js or somethiing)
        One component for showing all the existing () mapping and displaying them with info on the card. (limited info
          superhero name, comic img, show more button. 
        show more button (probably gonna be it's own component) we will want a delete button. We can also add a edit button inside of that component.
          We can decide when we get to it if we want to make it it's own component or just put it right there in that one.
          
        We could probably also add a component for our header, if we wanted to display and show things such as links. (like a nav bar). Because
          components somewhat act as partials in that sense. 
        Also probably add another component for a footer in case we want if it'll work with our data. 
        
    
    
