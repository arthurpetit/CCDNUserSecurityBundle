CCDNUser SecurityBundle README.
===============================


## Notes:  
  
This bundle is for the symfony framework and requires Symfony 2.0.x and PHP 5.3.6
  
This project uses Doctrine 2.0.x and so does not require any specific database.
  

This file is part of the CCDNUser bundles(s)

(c) CCDN (c) CodeConsortium <http://www.codeconsortium.com/> 

Available on github <http://www.github.com/codeconsortium/>

Theme and Sprite graphics courtesy of [twitter bootstrap](http://twitter.github.com/bootstrap/index.html) and [GLYPHICONS](http://glyphicons.com/).

Other graphics are works of CodeConsortium.

For the full copyright and license information, please view the LICENSE
file that was distributed with this source code.

## Description:

Use this bundle to redirect users upon login/logout success to the last page they were on.

## Features.

SecurityBundle Provides the following features:

1. Redirect user to last page they were on upon successful login.
2. Redirect user to last page they were on upon successful logout.
3. Prevent brute force attacks being carried out by limiting number of login attempts:
	1. When first limit is reached, redirect to an account recovery page.
	2. When secondary limit is reached, return an HTTP 500 status to block login pages etc.
4. All limits are configurable.
5. Routes to block are configurable.
6. Route for account recovery page is configurable.

## Documentation.

Documentation can be found in the `Resources/doc/index.md` file in this bundle:

[Read the Documentation](http://github.com/codeconsortium/CCDNUserSecurityBundle/blob/master/Resources/doc/index.md).

## Installation.

All the installation instructions are located in [documentation](http://github.com/codeconsortium/CCDNUserSecurityBundle/blob/master/Resources/doc/install.md).

## License.

This software is licensed under the MIT license. See the complete license file in the bundle:

	Resources/meta/LICENSE

[Read the License](http://github.com/codeconsortium/CCDNUserSecurity/blob/master/Resources/meta/LICENSE).

## About.

[CCDNUser SecurityBundle](http://github.com/codeconsortium/CCDNUserSecurityBundle) is free software from [Code Consortium](http://www.codeconsortium.com). 
See also the list of [contributors](http://github.com/codeconsortium/CCDNUserSecurityBundle/contributors).

## Reporting an issue or feature request.

Issues and feature requests are tracked in the [Github issue tracker](http://github.com/codeconsortium/CCDNUserSecurityBundle/issues).

Discussions and debates on the project can be further discussed at [Code Consortium](http://www.codeconsortium.com).
