<h1>Clean less project</h1>
All configured with grunt.<br/>
<ul>
    <li>Npm must be instaled</li>
    <li>To setup all modules use comand in terminal "npm instal" in this directore</li>
    <li>Add your custom styles to development/less/main.less. They compile to css/main.css and then minify to css/main.min.css</li>
    <li>Add your custom libs to development/libs. Styles of libs should be in .css and .js format. Otherwise add new config to Gruntfile.js. Styles also compile to css/main.css then minify to css/main.min.css. Scripts concat to development/js/concat_scripts.js</li>
    <li>Add your custome js code to development/js/custom.js it will concat to development/js/concat_scripts.js</li>
    <li>Then all scripts from development/js/concat_scripts.js uglify to scripts/scripts.min.js</li>
    <li>All styles compile to css/styles.css</li>
    <li>To run use "grunt" in terminal<li/>
</ul>
