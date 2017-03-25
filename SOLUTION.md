# SOLUTION

## DISCLAIMER : DO NOT CHEAT !

### STEP 1

**JS**
`

function stackMenu() {
	
}

function stackMenuMobile() {
	
}

function checkResolution() {
		if ($(this).width() < 480 ) {
			stackMenuMobile();
		}
		else {
			stackMenu();
		}
	});
}

$(document).ready(function() {

	checkResolution();

	$(window).on("resize", function(e) {
		checkResolution();
	});
});
`

### STEP 2
