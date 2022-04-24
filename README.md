https://github.com/coderbase-it/formation-angular-avance-starter-main
https://angular.io/guide/service-worker-getting-started

# Branche PWA 
ng add @angular/pwa

ng serve does not work with service workers, you must use a separate HTTP server to test your project locally
"pwa-dev":"http-server -p 8080 -c-1 dist/crm" ( package.json)
http://localhost:8080
