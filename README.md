Hello World for AngularJS 

This is the simplest form of AngularJS code. 

AngularJS ( ng in short ) uses MVC architecture at client side. 
It uses custom HTML tags, so it appears like we dont need to use any javascript to start with. 

<code>ng-app</code> tag is used to mark the scope where angular can be used. We added that in <code>&lt;body&gt;</code> to specify whole body is used for angular. 

<code>ng-init</code> tag is used to initialize values. Here we used it to add
some predefined value to <code>model</codea>. Remove <code>ng-init</code> and
check how it behaves

<code>ng-model</code> tag stores the data and it can be used to write/update or view anywhere else in the page. 
We don't need to write anymore code to add events to the model. Whenever the model changes , its updated in the page wherever it is used. 

<code>{{  }}</code>  are used to display the model value on the page 


keywords : <code>ng-app</code> <code>ng-init </code><code>ng-model </code>
