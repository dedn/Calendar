# Calendar
For the implementation of the calendar behavior logic I used:
<li> Bootstrap Sass
<li> Mixins or @extend for classes bootstrap
<li> The names of the classes according to BEM

Preview http://dedn.github.io/semantic_page/

### Project structure
     app /                                   :complete application   
          js/main.js                         :script to work Tabs or Main Menu
          html5shiv/                         :polyfill
          respond/                           :polyfill
          img/                               :project pictures   
    html /                                   :working directory for html 
    scss /                                   :working directory for scss file  
         includes/_header.scss               :header styles
         includes/_general_styles.scss       :the main styles of container styles
         includes/_navigation_section.scss   :navigation block style
         includes/_main.scss                 :portfolio styles
         includes/_form.scss                 :form page styles
         includes/_footer.scss               :foooter styles
         includes/_normalize.scss            :by Nicolas Gallagher and Jonathan Neal
         package.json                        :dependencies file
         gulpfile.js                         :configuration gulp file 
