# scss-to-css
Compile SCSS to CSS using the sass command.

1) Install SASS. 
Start by installing SASS on your Mac if you haven't already. Open your terminal and run the following command:

<code>gem install sass</code>

<code>brew install sass/sass/sass</code>

<code>npm install -g sass</code>

or visit the sass site for more installation options: https://sass-lang.com/install/

2. Navigate to the SCSS directory: 
Use the `cd` command in the Terminal to navigate to the directory where your SCSS files are located. 
For example, if your SCSS files are in a folder named "styles" on your desktop, you can use the following command:

<code>cd ~/Desktop/scss-to-css</code>

3. Convert SCSS to CSS: 
Once you are in the correct directory, run the following command in the Terminal to convert the SCSS files to CSS:

Same folder:
<code>sass --watch style.scss style.css</code>

Different folder:
<code>sass --watch SCSS/style.scss CSS/style.css</code>

This command tells SASS to watch for changes in the SCSS file and automatically convert it to CSS whenever you save any modifications.

4. Verify the conversion: 
After running the command, SASS will continuously monitor the SCSS file for changes. 
Whenever you make changes and save the SCSS file, SASS will automatically generate the corresponding CSS file. You can verify the conversion by checking the output.css file in the same directory.

By following these steps, you can easily convert SCSS files to CSS using SASS on your Mac. 
Remember to save your SCSS file after making any changes to trigger the automatic conversion process.
