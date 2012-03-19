This sample shows how to wrap text properly in things like activity feeds etc, where the area for user entered text is well defined.

The magic is with the following styles:

<pre>

 -ms-word-break: break-all;
     word-break: break-all;
     word-break: break-word;

-webkit-hyphens: auto;
   -moz-hyphens: auto;
        hyphens: auto;

</pre>