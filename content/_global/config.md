+++
fragment = "config"

[[config]]
  type = "css" # Acceptable values are icon, meta, link, css, js. Default is empty. Would not add anything on empty.
  block = true # If set to true, would inject the code to the <head> tag. Default is false
  html = "<link rel='stylesheet' href='/css/user.css'>" # HTML code injected directly to the page. Default is empty.
  #file = "/style/user.css" # Path to file, can be on page or in static/ directory. Default is empty.

+++
