Learning Rails
==

Learning rails with a tutorial from the RailsApps project.

export GMAIL_USERNAME="keith.turner.2.0@gmail.com"
export GMAIL_PASSWORD='"Ach13v3_00"'
export MAILCHIMP_API_KEY="026537a57c2875eb9eb37b4c78596065-us12"
export MAILCHIMP_LIST_ID="208dde1358"
export OWNER_EMAIL="keith.turner.2.0@gmail.com"


--------------------------------------


development:
  email_provider_username: <%= ENV[keith.turner.2.0@gmail.com] %>
  email_provider_password: <%= ENV[Ach13v3_00_xxx] %>
  domain_name: example.com
  mailchimp_api_key: <%= ENV[026537a57c2875eb9eb37b4c78596065-us12] %>
  mailchimp_list_id: <%= ENV[208dde1358] %>
  owner_email: <%= ENV[keith.turner.2.0@gmail.com] %>
  secret_key_base: very_long_random_string

test:
  secret_key_base: very_long_random_string

# Do not keep production secrets in the repository,
# instead read values from the environment.
production:
  email_provider_username: <%= ENV[keith.turner.2.0@gmail.com] %>
  email_provider_password: <%= ENV[Ach13v3_00_xxx] %>
  domain_name: <%= ENV["DOMAIN_NAME"] %>
  mailchimp_api_key: <%= ENV[026537a57c2875eb9eb37b4c78596065-us12] %> 
  mailchimp_list_id: <%= ENV[208dde1358] %> 
  owner_email: <%= ENV[keith.turner.2.0@gmail.com] %>
  secret_key_base: <%= ENV["SECRET_KEY_BASE"] %>
  