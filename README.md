Gravatar
==================

Installation & Configuration
-------------

To install

    ppm install gravatar


example to add library:
	
	$di->set('gravatar', function () {
	    $gravatar = new gravatarppm\Gravatar();
	    return $gravatar;
	});


execute in controller

	// return the image
	$this->gravatar->get('email@example.com');