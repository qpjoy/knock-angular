npm i @angular/cli -g
ng new my-dream-app --skip-install
ng serve
ng doc component
ng serve --help
ng lint
ng test
ng e2e
ng build
ng serve -o
ng -v

npm list -g @angular/cli --depth=0
ng new ngtest

ng new --help
ng new my-app --dry-run
ng new my-app --skip-install
ng new my-app2 --prefix acme --skip-install
ng new my-app2 --skip-tests --prefix acme --skip-install
ng new my-app2 --routing --skip-tests --prefix acme --skip-install --style scss
ng new my-app2 -stS --routing --style scss


ng new my-app7 --prefix jp --style scss

ng config schematics.@schematics/angular:component.styleext scss

ng lint my-app7 --format stylish

ng lint my-app7 --fix

blueprints

ng generate component customer   => ng g c customer
ng generate service customer-data

ng generate component pet --inline-template --inline-style
ng g c pet -ts
ng g c pet --flat
ng g c pet -st --flat --prefix my

ng g c orders --view-encapsulation Emulated -d
ng g c orders -v Emulated -c OnPush

ng g d search-box -d
ng g d search-box
ng g d search-box2 --flat false -d

ng g s sales-data

ng g cl models/customer
ng g i models/person
ng g e models/gender
ng g p init-caps -d
ng g p shared/init-caps -m app.module
ng g m login -d
ng g m login --spec false -d

ng g m login --spec false -m app.module
ng g c login -d

ng g c login/foo -m app.module -d



ng g directive search      d
ng g service customer-data s
ng g pipe init-caps        p
ng g class customer-model  cl
ng g interface orders      i
ng g enum gender           e

ng g module admin
ng g m sales --routing

ng new angular-routing --routing -d

ng g c dashboard

{path:'', pathMatch: 'full', redirectTo: 'dashboard'}

ng g m admin --routing -m app.module -d
ng g c admin
ng g c admin/email-blast

npm i webpack-bundle-analyzer -D
ng build --stats-json
npx webpack-bundle-analyzer dist/my-app/stats.json

ng build --prod
ng build --aot

ng serve --port 8262 -o

ng add @angular/material
ng g @angular/material:material-nav --name nav
ng g @angular/material:material-dashboard --name dashboard
ng g @angular/material:material-table --name customer-list



ng test --code-coverage

ng update
ng update --all
ng update --force
ng update @angular/material @angular/core

ng generate --help
ng generate application


ng generate library my-lib
ng build my-lib

ng generate library my-lib
ng g s logger --project my-lib
ng build my-lib --prod


ng serve --prod -o


