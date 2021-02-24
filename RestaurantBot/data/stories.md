## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Pune"}
    - slot{"location": "Pune"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email{"more_info_desired": "Yes"}
    - slot{"more_info_desired": "Yes"}
    - utter_ask_email
* send_email{"email": "gunavadlamudi83@gmail.com"}
    - slot{"email": "gunavadlamudi83@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
    - action_restart

## interactive_story_basic
* greet
    - utter_greet
* restaurant_search{"location": "Faridabad"}
    - slot{"location": "Faridabad"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email{"more_info_desired": "Yes"}
    - slot{"more_info_desired": "Yes"}
    - utter_ask_email
* send_email{"email": "gunavadlamudi83@gmail.com"}
    - slot{"email": "gunavadlamudi83@gmail.com"}
    - action_send_email
* exit
    - utter_goodbye
    - action_restart

## interactive_story__not_operational_continue
* greet
    - utter_greet
* restaurant_search{"location": "Allahabad"}
    - slot{"location": "Allahabad"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_no_operations
* location_fix{"ask_location_again": "Yes"}
    - slot{"ask_location_again": "Yes"}
    - utter_ask_location
* restaurant_search{"location": "Lucknow"}
    - slot{"location": "Lucknow"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email{"more_info_desired": "Yes"}
    - slot{"more_info_desired": "Yes"}
    - utter_ask_email
* send_email{"email": "gunavadlamudi83@gmail.com"}
    - slot{"email": "gunavadlamudi83@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
    - action_restart


## interactive_story_no_restaurant_found
* greet{"greet": "yello"}
    - utter_greet
* restaurant_search{"location": "Chennai"}
    - slot{"location": "Chennai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budget": "<300"}
    - slot{"budget": "<300"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
* exit
    - utter_try_again_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Chennai"}
    - slot{"location": "Chennai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "American"}
    - slot{"cuisine": "American"}
    - utter_ask_budget
* restaurant_search{"budget": "<300"}
    - slot{"budget": "<300"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_try_again_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Hyderabad"}
    - slot{"location": "Hyderabad"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* exit{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Pune"}
    - slot{"location": "Pune"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budget": "<300"}
    - slot{"budget": "<300"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_try_again_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "American", "location": "Kochi"}
    - slot{"cuisine": "American"}
    - slot{"location": "Kochi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email{"more_info_desired": "Yes"}
    - slot{"more_info_desired": "Yes"}
    - utter_ask_email
* send_email{"email": "gunavadlamudi83@gmail.com"}
    - slot{"email": "gunavadlamudi83@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Chennai"}
    - slot{"location": "Chennai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* exit{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart

## interactive_story_2
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Chennai"}
    - slot{"location": "Chennai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* exit{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Goa"}
    - slot{"location": "Goa"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_try_again_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "American", "location": "Chennai"}
    - slot{"cuisine": "American"}
    - slot{"location": "Chennai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* exit{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart

## interactive_story_2
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "goa"}
    - slot{"location": "goa"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_try_again_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "Mexican", "location": "Hyderabad"}
    - slot{"cuisine": "Mexican"}
    - slot{"location": "Hyderabad"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* exit{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "Mexican", "location": "Delhi"}
    - slot{"cuisine": "Mexican"}
    - slot{"location": "Delhi"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* continue{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart

# interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "Italian", "location": "Jaipur"}
    - slot{"cuisine": "Italian"}
    - slot{"location": "Jaipur"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* continue{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart

# interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "North Indian", "location": "Faridabad"}
    - slot{"cuisine": "North Indian"}
    - slot{"location": "Faridabad"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* continue{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart

# interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "South Indian", "location": "Lucknow"}
    - slot{"cuisine": "South Indian"}
    - slot{"location": "Lucknow"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* continue{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Bombay"}
    - slot{"location": "Bombay"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* continue{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Mumbai"}
    - slot{"location": "Mumbai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* continue{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Vellore"}
    - slot{"location": "Vellore"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* continue{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart
## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Chennai"}
    - slot{"location": "Chennai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "American"}
    - slot{"cuisine": "American"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* continue{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart

## interactive_story_1
* greet{"greet": "yello"}
    - utter_greet
* restaurant_search{"cuisine": "CHinese", "location": "Gurgaon"}
    - slot{"cuisine": "CHinese"}
    - slot{"location": "Gurgaon"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email{"more_info_desired": "Yes"}
    - slot{"more_info_desired": "Yes"}
    - utter_ask_email
* send_email{"email": "karthikkv2394@gmail.com"}
    - slot{"email": "karthikkv2394@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Jaipur"}
    - slot{"location": "Jaipur"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email{"more_info_desired": "Yes"}
    - slot{"more_info_desired": "Yes"}
    - utter_ask_email
* send_email{"email": "gunavadlamudi83@gmail.com"}
    - slot{"email": "gunavadlamudi83@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "surat"}
    - slot{"location": "surat"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email{"more_info_desired": "Yes"}
    - slot{"more_info_desired": "Yes"}
    - utter_ask_email
* send_email{"email": "gunavadlamudi83@gmail.com"}
    - slot{"email": "gunavadlamudi83@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
    - action_restart

# interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "surat"}
    - slot{"location": "surat"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Mexican"}
    - slot{"cuisine": "Mexican"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email{"more_info_desired": "Yes"}
    - slot{"more_info_desired": "Yes"}
    - utter_ask_email
* send_email{"email": "gunavadlamudi83@gmail.com"}
    - slot{"email": "gunavadlamudi83@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
    - action_restart

# interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "nagpur"}
    - slot{"location": "nagpur"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email{"more_info_desired": "Yes"}
    - slot{"more_info_desired": "Yes"}
    - utter_ask_email
* send_email{"email": "gunavadlamudi83@gmail.com"}
    - slot{"email": "gunavadlamudi83@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
    - action_restart

# interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "patna"}
    - slot{"location": "patna"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "American"}
    - slot{"cuisine": "American"}
    - utter_ask_budget
* restaurant_search{"budget": ">700"}
    - slot{"budget": ">700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email{"more_info_desired": "Yes"}
    - slot{"more_info_desired": "Yes"}
    - utter_ask_email
* send_email{"email": "gunavadlamudi83@gmail.com"}
    - slot{"email": "gunavadlamudi83@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Kerala"}
    - slot{"location": "Kerala"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_no_operations
* location_fix{"ask_location_again": "Yes"}
    - slot{"ask_location_again": "Yes"}
    - utter_ask_location
* restaurant_search{"location": "Chennai"}
    - slot{"location": "Chennai"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": true}
    - utter_ask_top_ten
* send_email{"more_info_desired": "Yes"}
    - slot{"more_info_desired": "Yes"}
    - utter_ask_email
* send_email{"email": "gunavadlamudi83@gmail.com"}
    - slot{"email": "gunavadlamudi83@gmail.com"}
    - action_send_email
    - slot{"mail_sent": true}
    - utter_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "gurgam"}
    - slot{"location": "gurgam"}
    - action_check_location
    - slot{"location_valid": false}
    - slot{"location_operational": false}
    - utter_location_not_found
    - utter_try_again_goodbye
    - action_restart
 
 ## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "mubaim"}
    - slot{"location": "mubaim"}
    - action_check_location
    - slot{"location_valid": false}
    - slot{"location_operational": false}
    - utter_location_not_found
    - utter_try_again_goodbye
    - action_restart
    
## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "vsdaf"}
    - slot{"location": "vsdaf"}
    - action_check_location
    - slot{"location_valid": false}
    - slot{"location_operational": false}
    - utter_location_not_found
    - utter_try_again_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "sdf"}
    - slot{"location": "sdf"}
    - action_check_location
    - slot{"location_valid": false}
    - slot{"location_operational": false}
    - utter_location_not_found
    - utter_try_again_goodbye
    - action_restart
    
## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "garbageae"}
    - slot{"location": "garbageae"}
    - action_check_location
    - slot{"location_valid": false}
    - slot{"location_operational": false}
    - utter_location_not_found
    - utter_try_again_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "asfasfaefawaf"}
    - slot{"location": "asfasfaefawaf"}
    - action_check_location
    - slot{"location_valid": false}
    - slot{"location_operational": false}
    - utter_location_not_found
    - utter_try_again_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* greet

## interactive_story_2
* greet
    - utter_greet
* restaurant_search{"location": "New York"}
    - slot{"location": "New York"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_no_operations
* location_fix{"ask_location_again": "Yes"}
    - slot{"ask_location_again": "Yes"}
    - utter_ask_location
* restaurant_search{"location": "goa"}
    - slot{"location": "goa"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_try_again_goodbye
    - action_restart

## interactive_story_2
* greet
    - utter_greet
* restaurant_search{"location": "New Jersey"}
    - slot{"location": "New Jersey"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_no_operations
* location_fix{"ask_location_again": "Yes"}
    - slot{"ask_location_again": "Yes"}
    - utter_ask_location
* restaurant_search{"location": "Patna"}
    - slot{"location": "Patna"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budget": "300-700"}
    - slot{"budget": "300-700"}
    - action_search_restaurants
    - slot{"found_restaurants": false}
    - utter_try_again_goodbye
    - action_restart
## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Ohio"}
    - slot{"location": "Ohio"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_no_operations
* greet{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Liverpool"}
    - slot{"location": "Liverpool"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_no_operations
* greet{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Manchester"}
    - slot{"location": "Manchester"}
    - action_check_location
    - slot{"location_valid": true}
    - slot{"location_operational": false}
    - utter_no_operations
* greet{"more_info_desired": "No"}
    - slot{"more_info_desired": "No"}
    - utter_goodbye
    - action_restart
