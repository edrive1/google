# google
.fluid-container
  .toolbar
    ul
      li: a(href="#Gmail") Gmail
      li: a(href="#Images") Images
      li: a(href="#"): i.material-iconsapps
      li: a(href="#"): i.material-iconsnotifications
      li: img(src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/59615/icon--profile.png")
      
  main.home
    .logo
    form
      input.search(type="text" placeholder="")
      .button-group
        button.button.button-default.g-search(type="submit")
          | Google Search
        button.button.button-default.lucky(type="submit")
          | I'm Feeling Lucky
          
  .footer
    ul
      li: a(href="#Advertising")
      li: a(href="#Business")
      li: a(href="#About")
      
    ul
      li: a(href="#Settings")
      li: a(href="#Terms")
      li: a(href="#Privacy")
