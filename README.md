# laraveltest

  Configuration details to run application -

        1.Update database details in  .env file-
                    DB_DATABASE=employee_db
                    DB_USERNAME=root
                    DB_PASSWORD=root_123

       2.If you are changing folder path please update in -
              'employee_demo/public/js/controller.js' with following changes -

              var employeeApp = angular.module('employeeApp', ['ngFileUpload']).
                  constant('API_URL', 'http://localhost/employee_demo/public/');
