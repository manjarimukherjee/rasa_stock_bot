## greeting start with stock
* welcome_greet
  - utter_welcome_greet
> start_questions_on_stock
> showing_response_stock
## stock questions
* init_request_stock
  - utter_init_request_stock
> showing_response_stock
## greeting start with metal
* welcome_greet
  - utter_welcome_greet
> start_questions_on_metal
> showing_response_metal
## metal questions
* init_request_metal
  - utter_init_request_metal
> showing_response_metal
## further response stock
* response_name_company
  - action_hello_world
  - utter_did_that_help
## further response metal
* response_name_metal
  - action_hello
  - utter_did_that_help
## show chart of stock
* show_chart
  - action_chart
  - utter_did_that_help

