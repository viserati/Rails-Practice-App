Learning Rails
==

Rails practice project.

export GMAIL_USERNAME=
export GMAIL_PASSWORD=
export MAILCHIMP_API_KEY=
export MAILCHIMP_LIST_ID=
export OWNER_EMAIL=


--------------------------------------


development: 
  email_provider_password: 
  domain_name: example.com
  mailchimp_api_key: 
  mailchimp_list_id: 
  owner_email: 
  secret_key_base: very_long_random_string

test:
  secret_key_base: very_long_random_string

# Do not keep production secrets in the repository,
# instead read values from the environment.
production:
  email_provider_username:
  email_provider_password: 
  domain_name:
  mailchimp_api_key:
  mailchimp_list_id:
  owner_email:
  secret_key_base:
  
