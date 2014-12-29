

<h1>Javascript Style Guide</h1>


<h2>names, declaration and calling</h2>

<ul>
	<li>
		<p>
			Naming conventions
		</p>

		<ul>
			<li>Always use lowerCamelCase.</li>
			<li>Never use hungarian notation (m_memberVariable).</li>
			<li>Always prepend private member variable names with an underscore.</li>
		</ul>
	</li>

	<li>
		<p>
			Create objects and functions at least one namespace off of global scope.<br />
			&nbsp;<i>e.g. where our initial desire is to create the "foo" object</i>
		</p>

<pre>
	var axonom = axonom || { };

	axonom.foo = {
		thing: "stuff",
 		bar: function () { ... } 
	};
</pre>
	</li>

	<li>
		<p>
			Explicitly specify the "window" object when using its properties and functions.<br />
			&nbsp;<i>e.g.</i>
		</p>

<pre>
	window.parseInt( "34" );
	window.clearTimeout( timer );
	window.addEventListener( "load", completed, false );
</pre>
	</li>


	<li>
		<p>
			Always declare variables with var (or let/const, when ECMAScript 6.0 gains support). This ensures that variables are not accessible from the global scope. It is also a readability issue ("To which scope is this variable declared?").
		</p>
	</li>

	<li>
		<p>
			Prefer using one "var" per set of declarations and one line per variable.
		</p>

			Avoid:
<pre>
	var thing;
	var stuff;
	var foo;
	var bar;
</pre>

			Avoid:
<pre>
	var thing, stuff, foo, bar;
</pre>

			Prefer:
<pre>
	var thing,
		stuff,
		foo,
		bar;
</pre>
	</li>

	<li>
		<p>
			Variables should be declared as early as possible in thier respective scope, <br />
			&nbsp;even when it seperates declaration from assignment.
		</p>
			
		<p>
			This means that the following function in ECMAScript 5 should read:
		</p>

<pre>
	function prepareUrl(url) {
		return url.replace(/\{([^}]+)\}/g, function ( token, value ) {
			var fieldName; // <--- declared here

			if ( value.slice( 0, 2 ) == "v:" ) {
				fieldName = value.slice( 2 ); // <--- assigned here
				return cartServiceInstance.appProfile.contextualData[ fieldName ];
			}

			return token;
		});
	};
</pre>

		<p>
			Whereas an ECMAScript 6 impl. may use "let" to join the declaration and assignment in block scope:
		</p>

<pre>
	function prepareUrl(url) {
		return url.replace(/\{([^}]+)\}/g, function ( token, value ) {
			if ( value.slice( 0, 2 ) == "v:" ) {
				let fieldName = value.slice( 2 ); // <--- initialized as first statement in scope
				return cartServiceInstance.appProfile.contextualData[ fieldName ];
			}

			return token;
		});
	};
</pre>
	</li>
</ul>


<h2>white space</h2>

<ul>
	<li>
		<p>
			Use four spaces for one unit of indent. Do not use tab characters. Visual Studio handles tab conversion to this exact format by default. If you use Visual Studio and have not changed this setting, you may ignore this line-item.
		</p>
	</li>

	<li>
		<p>Prefer to seperate symbols from parens and brackets with spaces</p>
			Avoid:
<pre>
	if (condition) ;
	<while (condition) ;
	<for (var i = 0; i < 100; i++) ;
</pre>
			
			Prefer:
<pre>
	if ( condition ) ;
	while ( condition ) ;
	for ( var i = 0; i < 100; i++ ) ;
</pre>
	</li>

	<li>
		<p>Prefer one space between brackets and braces for object and array initializers</p>

			Avoid: 
<pre>
	var a = []; 
	var o = {};
</pre>

			Prefer: 
<pre>
	var a = [ ];
	var o = { };
</pre>
	</li>

	<li>
		<p>
			Use newlines to group logically related pieces of code. (google styleguide)<br />
			&nbsp;<i>e.g.</i>
					
<pre>
	doSomethingTo( x );
	doSomethingElseTo( x );
	andThen( x );

	nowDoSomethingWith( y );

	andNowWith( z );
</pre>
		</p>
	</li>

	<li>
		<p>
			If a function literal is anonymous, there should be one space between the word function and the ( (left parenthesis). If the space is omited, then it can appear that the function's name is function, which is an incorrect reading. (crockford)
		</p>

<pre>
    div.onclick = function ( e ) {
        return false;
    };

    var that = {
        method: function () {
            return this.datum;
        },
        datum: 0
    };
</pre>
    </li>
</ul>


<h2>new lines</h2>

<ul>
	<li>
		<p>Leave a line in between object literal function definitions.</p>
		
		<p>
			Avoid:
<pre>
	var axonom = {
		foo: function () {
		 	// stuff
		 },
		bar: function () {
		 	// stuff
		 },
		stuff: function () {
		 	// stuff
		 }
	};
</pre>
		</p>
		
					Prefer:
<pre>
	var axonom = {
		foo: function () {
		 	// stuff
		 },
		 
		bar: function () {
		 	// stuff
		 },
		 
		stuff: function () {
		 	// stuff
		 }
	};
</pre>
		</p>
	</li>

	<li>
		<p>Avoid using multiline string literals (google styleguide)</p>

		<p>
			Never:<br />

<pre>
	var myString = 'A rather long string of English text, an error message \
	                actually that just keeps going and going -- an error \
	                message to make the Energizer bunny blush (right through \
	                those Schwarzenegger shades)! Where was I? Oh yes, \
	                you\'ve got an error and all the extraneous whitespace is \
	                just gravy.  Have a nice day.';
</pre>
			<br />
			The whitespace at the beginning of each line can't be safely stripped at compile time; whitespace after the slash will result in tricky errors; and while most script engines support this, it is not part of ECMAScript.
		</p>

		<p>
			Always:<br />

<pre>
	var myString = 'A rather long string of English text, an error message ' +
	    'actually that just keeps going and going -- an error ' +
	    'message to make the Energizer bunny blush (right through ' +
	    'those Schwarzenegger shades)! Where was I? Oh yes, ' +
	    'you\'ve got an error and all the extraneous whitespace is ' +
	    'just gravy.  Have a nice day.';
</pre>
	    </p>
    </li>

    <li>
		<p>Binary and Ternary Operators (google styleguide)</p>

		<p>Always put the operator on the preceding line. This operator placement was initially agreed upon out of concerns about automatic semicolon insertion. In fact, semicolon insertion cannot happen before a binary operator, but new code should stick to this style for consistency.</p>

<pre>
	var x = a ? b : c;  // All on one line if it will fit.
</pre>

<pre>
	var y = a ?
	    longButSimpleOperandB : longButSimpleOperandC;
</pre>

<pre>
	// Indenting to the line position of the first operand is also OK.
	var z = a ?
	        moreComplicatedB :
	        moreComplicatedC;
</pre>

		<p>This includes the dot operator.</p>

<pre>
	var x = foo.bar().
	    doSomething().
	    doSomethingElse();
</pre>
    </li>

	<li>
		<p>Prefer to break object literal and array initializers out onto new lines</p>

		<p>
			Avoid:

<pre>
	var cartServiceInstance = {
		landingDept: { id: null, name: null, type: null, url: null, guide_id: null }
	}
</pre>
		</p>

		<p>
			Prefer:

<pre>
	var cartServiceInstance = {
		landingDept: { 
			id: null, 
			name: null, 
			type: null, 
			url: null, 
			guide_id: null 
		}
	}
</pre>
		</p>

		<p>
			Avoid:

<pre>
	var contrivedArray = [ Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, Saturday ];
</pre>
		</p>

		<p>
			Prefer:

<pre>
	var contrivedArray = [ 
		Sunday, 
		Monday, 
		Tuesday, 
		Wednesday, 
		Thursday, 
		Friday, 
		Saturday 
	];
</pre>
		</p>
	</li>
</ul>


<h2>syntax</h2>

<ul>
	<li>
		<p>Semicolons; use them.</p>
	</li>

	<li>
		<p>Prefer to refactor functions longer than 30 lines.</p>
	</li>
	
	<li>
		<p>Avoid checking in commented-out code.</p>
		
		<p>
			Avoid:
<pre>
	function CartGuideCtrl($scope, interviewer) {
		//$scope.$on('interviewStart', onInterviewStart);
		//$scope.$on('interviewFinish', onInterviewFinish);
		$scope.$on('interviewResponseSynced', onResponseSync);
		$scope.$on('enterPane', onPaneChange);
		$scope.$on('responseChanged', onResponseChange);
		interviewer.executionMode = "configurator";
		//interviewer.start(requestedGuideId, requestedGuideVersionId);
		
		...
	}
</pre>
	    	</p>
	    	
	    	<p>
	    		Prefer:
<pre>
	// Controller scoped to the PC section tabs and guide controls
	function CartGuideCtrl($scope, interviewer) {
		$scope.$on('interviewResponseSynced', onResponseSync);
		$scope.$on('enterPane', onPaneChange);
		$scope.$on('responseChanged', onResponseChange);
		interviewer.executionMode = "configurator";
		
		...
	}
</pre>
	    	</p>
	</li>
	
	<li>
		<p>
			Coerce to boolean where boolean is expected
		</p>

		<p>
			Avoid:
<pre>
	$.post( "axonom/stuff", this.handleCallback.bind( this, data.success ) );
</pre>
		</p>

		<p>
			Prefer:
<pre>
	$.post( "axonom/stuff", this.handleCallback.bind( this, !!data.success ) );
</pre>
		</p>
	</li>

	<li>
		<p>Avoid using window.eval().</p>
	</li>

	<li>
		<p>
			Avoid using self = this. Instead, use function.prototype.bind(), call() and apply().
		</p>

		<p>
			Avoid:

<pre>
	var axonom = {
		hasBeenClicked: false,

		init: function () {
			var self = this;

			$( ".widget" ).on( "click", function ( e ) {
				self.hasBeenClicked = true;
			});
		};
	};
</pre>
		</p>

		<p>
			Prefer:

<pre>
	var axonom = {
		hasBeenClicked: false,

		init: function () {
			$( ".widget" ).on( "click", this.handleClick.bind(this));
		},

		handleClick: function ( e ) {
			this.hasBeenClicked = true;
		}
	}
</pre>
		</p>
	</li>

	<li>
		<p>Avoid building on the prototype of native Javascript types. (e.g. Object.Prototype, Function.Prototype)</p>
	</li>

	<li>
		<p>
			Do not declare functions within blocks (google styleguide)
		</p>

		<p>
			Do not do this:
			
<pre>
	if ( x ) {
	  function foo() {}
	}
</pre>
			<p>
				While most script engines support Function Declarations within blocks it is not part of ECMAScript (see ECMA-262, clause 13 and 14). Worse implementations are inconsistent with each other and with future EcmaScript proposals. ECMAScript only allows for Function Declarations in the root statement list of a script or function. Instead use a variable declared with a Function Expression to define a function within a block:
			</p>

<pre>
	if ( x ) {
	  var foo = function() {};
	}
</pre>
		</p>
	</li>

	<li>
		<p>Prefer using braces for blocks</p>
	
		<p>
			Avoid:
<pre>
	if ( success ) return true;
</pre>
		</p>

		<p>
			Avoid:
<pre>
if ( success )
	return true;
</pre>
		</p>
	
		<p>
			Prefer:
<pre>
	if ( success ) {
		return true;
	}
</pre>
		</p>

		<p>
			This allows your peers to extend your block without having to perform the menial task of adding braces.
		</p>
	</li>

	<li>
		<p>Do not pass strings to window.setTimeout or window.setInterval. (crockford)</p>
	</li>

	<li>
		<p>Prefer double quotes ( " ) and avoid single quotes ( ' ).</p>
	</li>
</ul>


<h2>resources</h2>

<ul>
	<li>
		Closures:
		<ul>
			<li>http://jibbering.com/faq/notes/closures/</li>
			<li>http://benalman.com/news/2010/11/immediately-invoked-function-expression/</li>
		</ul>
	</li>

	<li>
		ECMAScript 6: 
		<ul>
			<li>https://leanpub.com/understandinges6/read</li>
		</ul>
	</li>

	<li>
		Sourcing information:
		<ul>
			<li>Avoid w3schools.com (see: w3fools.com)</li>
			<li>Prefer developer.mozilla.org</li>
		</ul>
	</li>

	<li>
		Feature support:
			<ul>
				<li>We support modern FF, modern Chrome and IE9+. </li>
				<li>Use Javascript features that are indicated as being supported by these browers by caniuse.com or MDN.</li>
			</ul>
	</li>
</ul>


<h2>references</h2>

<p>
	Google styleguide: https://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml
</p>

<p>
	Crockford's styleguide: http://javascript.crockford.com/code.html
</p>
