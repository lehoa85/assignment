NOTE:
+ Demo link:http://assignment.drupalthemes.us
 Admin account: admin/admin
+ For generating QR code, I chosen light weight library endroid/qr-code
+ The main of this assignment is custom module, so I write stylesheet on the module instead of create a theme
 and use default theme Olivero

Steps to deploy to your site

1. Copy module qrcode from modules/custom/qrcode to your drupal module folder

2. Enable the module, it will create everything as below automatically

    + Content type Product and fields of it
    + Block plugin called "QR code purchase"

3. Go to Block Layout link and put Block "QR code purchase" into Sidebar region
(I can assign this block into region automatically when module installing 
but will do it manually because it belong to region in theme using)

4. Go to Content link and input content for Product

5. Access product detail page to see the result

