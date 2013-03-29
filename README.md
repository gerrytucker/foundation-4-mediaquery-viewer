Foundation 4 Media Query Viewer
===============================

Foundation 4 removed the Media Query Viewer (or Toggle) component that was previously available in Foundation 3.

This script is a direct drop-in for Foundation 4 and has been updated to reflect the new F4 visibility classes.

Usage
-----

1.  Include the script in your page:

    <script src="javascripts/foundation-mediaQueryToggle.js"></script>
    
2.  Initialise the script from within your application:

    ;(function ($, window, document, undefined) {
      'use strict';
      
      $(document).foundationMediaQueryViewer();
      
    }(Foundation.zj, this, this.document));

3.  Press the 'M' key to toggle the viewer.
