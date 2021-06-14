class PasswordChecker:
    def take_input:
        #Take full user name, year of birth. as user what option (generate, check, or exit).

        first_name = input('Enter your first name:')
        last_name = input('Enter your last name')

        birth_year= input('Enter your year of birth:')

        check_password= input('do you want to check the password')
        generate_password = input('do you want to generate password')
        end_program= input('Do you want to exit the program:')

        if end_program == "end":
            break
        else:
            print('go again')