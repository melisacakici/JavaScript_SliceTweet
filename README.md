# JavaScript_SliceTweet
This JavaScript code is counting the tweet length and slice it to make the tweet short enough for sharing. It does not print more than 140 characters.

var tweet = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum tincidunt scelerisque quam id ultricies. Sed vestibulum viverra ipsum eu luctus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vitae tellus nec leo auctor sodales. Aliquam erat volutpat. Duis id ligula sit amet augue ultrices viverra a sit amet ante.";
var count = tweet.length;
alert("Count is : "+ count);

if(count > 140)
    alert("Your tweet is too long");

var sliceTweet = tweet.slice(0, 140);
alert(sliceTweet);

