+++
fragment = "contact"
#disabled = true
date = "2017-09-10"
weight = 80
background = "light"
form_name = "defaultContact"

title = "Kontakt"

# PostURL can be used with backends such as mailout from caddy
post_url = "https://example.com/mailout" #default: formspree.io
email = "mail@example.com"
button_text = "Wyślij" # defaults to theme default
netlify = true

# Optional google captcha
#[recaptcha]
#  sitekey = "6LfJMAoaAAAAAM1a7EsI_luMLwJLyYvL1oTNZgwE"

[message]
  #success = "" # defaults to theme default
  #error = "" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Nazwa *"
  #error = "" # defaults to theme default

[fields.email]
  text = "Email *"
  #error = "" # defaults to theme default

[fields.phone]
  text = "Numer telefonu *"
  #error = "" # defaults to theme default

[fields.message]
  text = "Twoja wiadomość *"
  #error = "" # defaults to theme default

+++
