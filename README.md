# sass-mixins

A collection of useful sass mixins - and associated folder of sublime snippets which can be fired with keywords.

mixins like these:

	//            color    		size    	transf 	 	spacn 	lin-heig   align 	weight  decora  style
	@include type($um-blue, 	rem(16)s, 	null, 		null, 	1.4em, 	   null, 	null, 	none, 	null);

	@include bgimage ('couple-rough.jpg', cover, 50%, 0);
	@include icon-query(expert-help, 50%, 72px, 1);
	@include transition(all, 0.08, 0, ease);
	@include position(absolute, 0, 0, 0, 60%, 0);
	@include bubbleArrow(30px, $um-grey-bg);
	@include gradient (red, green);
	@include rotate($angle);
	@include clearfix;
	@include bg($um-blue); //background

	@include b(red);    //border 1px
	@include b2(red);    //border 2px
	@include b3(red);    //border 3px

	@include bt(red);	//border-top
	@include bb(red);	//border-bottom
	@include br(red);	//border-right
	@include bl(red);	//border-left
