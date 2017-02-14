1. a. $( '.profile-image' ).attr( 'src', 'http://cdn.techgyd.com/no-user-profile-picture-whatsapp.jpg' );
   b. $( "#left-image" ).children().attr( 'src', 'https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcTj8W9mpTc7PvRYn9BYaw9aCaP4vDjXg9pF-7zblhK0eUtQayX28g' );

2. $( 'h1.highlight' ).text( 'Noah' );

3. $('#employment h3').text('Noah');

4. $('#time-travel').parent().remove('div');

5. $('body').css('background-color', 'red');

6. $('.highlight').css('background-color', 'blue');

7. $('h1').css('font-family', 'monospace');

8. $('.action-icon-bg').css('background-color', 'grey');

9. $('#name').attr('placeholder', 'identify yourself');

10. $('#message').attr('placeholder', 'state your business');

11. $('#name').attr('value', 'your nemesis');

12. $('#email').attr('value', 'koalathebear@gmail.com');

13. $( '#submit' ).attr( 'value', 'En garde!' );

Adding elements to DOM

1. $( '#right-image img' ).clone().appendTo( '.portfolio-container' );

2. for ( var i = 0; i < 10; i++ ) {$( '#right-image img' ).clone().appendTo( '.portfolio-container' );}
