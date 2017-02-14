1. $('.profile-image').attr("src", "http://cdn.akamai.steamstatic.com/steamcommunity/public/images/avatars/c9/c9a89e12b0a5db8b7212564c86f5fc026d50e1a5_full.jpg");

1. $('#left-image img').attr("src", "http://s1.picswalls.com/wallpapers/2015/12/12/beautiful-wallpaper-hd_1244185_294.jpg");

2. $('h1.highlight').text("Jurgen Hahn")

3. var suitcase = $('.icon-suitcase')
  $('#employment h3').html(suitcase).append('&nbsp; Emboilment')

4. $('#time-travel').parent().remove()

5. $('body').css('color', 'red')

6. $('.highlight').css('color', 'blue')

7. $('h1').css('font-family', 'monospace')

8. $('.action-icon-bg').css('background-color', 'blue')

9. $('#name').attr('placeholder', 'Identify Yourself')

10. $('#message').attr('placeholder', 'State Your Business')

11. $('#name').attr('value', 'your nemesis');

12. $('#email').attr('value', 'koalathebear@gmail.com');

13. $('#submit').attr('value', 'en garde')

1. $('#submit').attr('disabled', 'en garde')

2. $('.bio-info-value').empty()

1. $('#right-image img').clone().appendTo('section')

2. for (var i=0; i < 10; i++) {$('#right-image img').clone().appendTo('section')}

3. var listItem = document.createElement('li');
  //create a new <span> tag
  var leftSpan = document.createElement('span');
  var rightSpan = document.createElement('span');
  //make a "text node" in order to put text inside our new span
  var lastUpdated = document.createTextNode('Page last updated on');
  var today = document.createTextNode('2017/2/14');

  leftSpan.appendChild(lastUpdated);
  rightSpan.appendChild(today);

  listItem.appendChild(leftSpan);
  listItem.appendChild(rightSpan);

  var bio = document.getElementsByClassName('bio-info');
  bio[0].appendChild(listItem);
