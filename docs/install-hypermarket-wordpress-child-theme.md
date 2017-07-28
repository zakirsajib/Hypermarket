# Install and activate Hypermarket child theme

Before making changes to the theme code, we recommend that you install a [child theme](https://github.com/mahdiyazdani/Hypermarket-Child/releases). This ensures that your changes won’t be lost when updating to a new version of Hypermarket.

## WordPress admin panel

*(Recommended)*

* Start by [downloading the Hypermarket child theme](https://github.com/mahdiyazdani/Hypermarket-Child/releases).
* Go to **Appearance** » **Themes** and Click on the **Add New** button at the top.
* Click **Upload Theme** button.
* Click **Browse** and choose the file you just downloaded, then click **Install Now**.
* Once it is installed, click on the **activate** button, and you’ve successfully installed and activated the Hypermarket child theme.

## Manually - FTP method

* Start by [downloading the Hypermarket child theme](https://github.com/mahdiyazdani/Hypermarket-Child/releases).
* Upload the extracted folder of **hypermarket-child.zip** to the ```/wp-content/themes/``` dir on your server via FTP.
* Go to **Appearance** » **Themes**. 
* Activate Hypermarket child theme by clicking on the **activate** button.

## What is a child theme?

**A Child Theme is a theme** that inherits the same functionality and styling of another theme, called the parent theme. By creating and working on a child theme, you can add, modify or disable parts of your site without changing the original files of the parent theme.

You do not have to worry anymore about updates to the parent theme since there is no need to exclude your modified files from the updating process or to re-add your changes to fit the new version. After the creation of a Child Theme, you end up significantly speeding up your development time.

## Overriding Template Files

If you want to edit the code in the theme's template files like ```header.php```, ```index.php```, etc, you can just copy the file from the parent theme and put it into your child theme folder then edit it from there.

## Overriding Functions

If you want to edit the functions of the parent theme, for example, the ```hypermarket_comments_list()``` function, you can do that by copying only the function from the parent theme and put it into the "functions.php" file of your child theme.

!> Note that, you must copy only the ```function() {...}``` part, **NOT** including the ```function_exists()``` wrapper.

## Overriding Theme's CSS

You can do this by either using the **Additional CSS** section in WordPress Customizer or adding your custom CSS code into the ```assets/css/hypermarket-child.css``` file of your child theme.

?> Whenever you finished updating the parent theme, make sure to check all the code you use in your child theme and update them as necessary to reflect any changes in the parent theme. You might back up your custom code first, update the files with the latest version, then apply your custom code back.
By doing this, it ensures that the files and code in your child theme are always up-to-date and to prevent any problem that might occur.