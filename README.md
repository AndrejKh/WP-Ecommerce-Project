# [Website Project] e-Commerce
![e-Commerce logo]( https://github.com/williamniemiec/wp_eCommerce/blob/master/media/logo/logo.jpg)

This is a project about a website for e-Commerce. It is not a complete e-commerce system, however it serves as a basis for building one. This project uses [MVC pattern](https://github.com/williamniemiec/MVC-in-PHP), made in PHP.

<hr />

## Requirements
- password_strength
- jQuery
- Bootstrap 4
- Adblock disabled in the page (this is because adblock blocks urls with 'ad' in the name)

## Project organization
![](https://github.com/williamniemiec/wp_eCommerce/tree/master/media/uml/uml.png?raw=true)

### /
|Name| Type| Function
|------- | --- | ----
| media | `Directory`| Visual informations about the project
| src | `Directory`| Contains all website files
| .project| `File`| Contains all model application classes


### /src
|Name| Type| Function
|------- | --- | ----
| assets| `Directory`| Contains all application content files
| controllers | `Directory`| Contains all application controller classes
| core | `Directory`| Contains the classes responsable for the MVC operations
| models | `Directory`| Contains all application model classes
| vendor| `Directory`| Folder created by Composer - responsable for classes autoload
| views | `Directory`| Contains all application view classes
| &#46;buildpath| `File`| File created by IDE
| &#46;htaccess| `File`| Responsible for friendly url
| &#46;project | `File`| File created by IDE
| composer&#46;json | `File`| File created by Composer
| config&#46;py | `File`| Website configuration file (Database and website location)
| environment&#46;php | `File`| File responsible for defining which environment is in use
| index&#46;php | `File`| File responsible for starting the website


## Application photos
#### Home
![home](https://github.com/williamniemiec/wp_eCommerce/blob/master/media/app/home.png?raw=true)
#### About
![about](https://github.com/williamniemiec/wp_eCommerce/blob/master/media/app/about.png?raw=true)
#### Register
![register](https://github.com/williamniemiec/wp_eCommerce/blob/master/media/app/register.png?raw=true)
![register_success](https://github.com/williamniemiec/wp_eCommerce/blob/master/media/app/register-success.png?raw=true)
#### MyAds
![myAds](https://github.com/williamniemiec/wp_eCommerce/blob/master/media/app/myAds.png?raw=true)
#### EditAd
![editAd](https://github.com/williamniemiec/wp_eCommerce/blob/master/media/app/editAd.png?raw=true)
#### AddAd
![addAd](https://github.com/williamniemiec/wp_eCommerce/blob/master/media/app/addAd.png?raw=true)
#### Ad
![ad](https://github.com/williamniemiec/wp_eCommerce/blob/master/media/app/ad.png?raw=true)
