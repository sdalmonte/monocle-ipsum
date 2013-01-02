A repository for the Monocle Ipsum code, forked from Bacon-Ipsum https://github.com/petenelson/bacon-ipsum 

= What's in here? =

sdm-MonocleIpsumGenerator.php - Contains the MonocleIpsumGenerator class for generating bespoke filler text.  For example:

	require_once 'sdm-MonocleIpsumGenerator.php';
	$monocle_ipsum_generator = new MonocleIpsumGenerator();
	$bespoke_filler = $monocle_ipsum_generator->Make_Some_Meaty_Filler('economy-class', 3, true);


sdm-monocle-ipsum-form.php - WordPress plugin for generating the form you see on our home page as well as processing the form and outputting monocle ipsum filler.

sdm-monocle-ipsum-api.php - WordPress plugin for our JSON API.



Revision History

= v2.1.1 October 18, 2012 =
* Added 'doner' to the generator's list of meat (http://en.wikipedia.org/wiki/Doner_kebab)

= v2.1 July 21, 2012 =
* Changed the Make_Some_Meaty_Filler() function to return an array of paragraphs instead of straight HTML, added default parameters
* Added support for individual sentences
* Added sentence support to the API code, minor code refactoring
* Added more randomness to commas in a sentence.  Instead of always adding a 
  comma to a sentence with seven or more words, it will add one about 2/3rds of the time.
* Updated jQuery plugin and sample code to support sentences

= July 14, 2012 = 
* First public release (generator, form plugin and API plugin)

