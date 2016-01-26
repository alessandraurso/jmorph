### Welcome ###
Welcome fellow developer to the jmorph project!
Jmorph is a dynamic and highly structured javascipt namespace based library. Including support for UI elements such as tabs, trees, menus, expanders and built in ECMA html object support. Concepts from delegates, debugging, AJAX, exceptions, components, and controls are all included in this compact framework.  The library is very well structured with an SDK to help those who want to contribute.



---

### Overview ###
This library is intended to be a valuable resource for web masters, but more importantly it is designed to show how a javascript library can be organized, well documented, and much more scalable than just a basic scripting language.  In no way is this library going to compete with commercial or even massive open source projects like Yahoos YUI framework.  However it is a very tight, simple, and compact framework that can be used for professional and educational purposes.

![http://members.cox.net/clamle2/img_gcode/jmorph_main.jpg](http://members.cox.net/clamle2/img_gcode/jmorph_main.jpg)




---

### Docs ###
Because javascript is an object based language, and not a true OO language, some of the terminology in the provided documentation may not be completely compatible with OO concepts, however the feel and layout should resemble true OO languages like Java, C++, and C#.  The documentation is layed out very similar to javadocs help files.

![http://members.cox.net/clamle2/img_gcode/jmorph_docs.jpg](http://members.cox.net/clamle2/img_gcode/jmorph_docs.jpg)


---

### Setup ###
Setup is a snap!  [Download](http://code.google.com/p/jmorph/downloads/list) to any directory, unzip the archive and the project is ready to preview.  Inside each demo is a quick reference that allows web masters to simply plugin and go.  If you want to see how the API works just checkout the documentation, and a link to all the source code is available through your browser.


---

### Example ###
Below is the code used for a tab control.  Following the code is an example of the output.
Note that everything is stylesheet driven, so editing is very simple. Add the following code to any file and your control is ready to display.
```
        <script type='text/javascript' src='../source/base/jmorph.js'></script>
        <script type='text/javascript' src='../source/ui/tabcontrol.js'></script>
        <script type='text/javascript'>
            var TabControl = jmorph.UI.TabControl;
            function init() {	
                SampleTabs1 = new TabControl(document.getElementById("TabCtl"));
                SampleTabs1.Height = '50px';
                SampleTabs1.Width  = '400px';
                SampleTabs1.Bind();
            }
        </script>
        <body onload='init()'/>

        <div id="TabCtl">
          <label>Label 1</label>
          <label>Label 2</label>
          <div>tab 1 data </div>
          <div>tab 2 data</div>	
        </div>
    

```
![http://members.cox.net/clamle2/img_gcode/jmorph_tab1.jpg](http://members.cox.net/clamle2/img_gcode/jmorph_tab1.jpg)

This is the output from the code above.  This is just a very basic implementation of one of the controls.



---

### Developers ###
If your intrested in contributing to the jmorph project
[contact me by email](mailto:cory@lamle.org).  You can also conctact me through my personal web site  [lamle.og](http://www.lamle.org).