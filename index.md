<!DOCTYPE html>
<html>
<title>CHOW-DOWN</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Inconsolata">
<style>
body, html {
  height: 100%;
  font-family: "Inconsolata", sans-serif;
}

.bgimg {
  background-position: center;
  background-size: cover;
  background-image: url("./images/phonto11.JPG");
  min-height: 75%;
}

.menu {
  display: none;
}
</style>
<body>

<!-- Links (sit on top) -->
<div class="w3-top">
  <div class="w3-row w3-padding w3-black">
    <div class="w3-col s3">
      <a href="#" class="w3-button w3-block w3-black">HOME</a>
    </div>
    <div class="w3-col s3">
      <a href="#about" class="w3-button w3-block w3-black">ABOUT</a>
    </div>
    <div class="w3-col s3">
      <a href="#review" class="w3-button w3-block w3-black">REVIEW</a>
    </div>
    <div class="w3-col s3">
      <a href="#community" class="w3-button w3-block w3-black">COMMUNITY</a>
    </div>
  </div>
</div>

<!-- Header with image -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-bottomleft w3-center w3-padding-large w3-hide-small">
  </div>
  <div class="w3-display-middle w3-center">
  </div>
  <div class="w3-display-bottomright w3-center w3-padding-large">
  </div>
</header>

<!-- Add a background color and large text to the whole page -->
<div class="w3-sand w3-large">

<!-- About Container -->
<div class="w3-container" id="about">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-64"><span class="w3-tag w3-wide">ABOUT US</span></h5>
    <p>We started as two second-year students at the Sauder School of Business with a passion for food and an eye for design. ChowDown started off as a joke, but after hundreds of discussions later, we decided to bring our ideas to life and start a community of foodies focused on finding local eats and finding hole-in-the wall spots to support small businesses in and out of the Vancouver area. We love listening to stories and sharing how these businesses started so if your restaurant would like a feature, feel free to reach out to us anytime!
    <p>Current Authors:
      Nara Jung
      Elizabeth Hui
      Dilanka Wijesinghe
      Alieen Fang </p>
    <div class="w3-panel w3-leftbar w3-light-grey">
      <p><i>"People who love to eat are always the best people"</i></p>
      <p>Julia Child</p>
    </div>
  </div>
</div>

<!-- Review Container -->
<div class="w3-container" id="review">
  <div class="w3-content" style="max-width:700px">
 
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">OUR REVIEWS</span></h5>
    <div id="Green Leaf Cafe">
      <h1>Green Leaf Cafe</h1>
      <img src="./images/I1.jpeg" style="width:100%;max-width:1000px" class="w3-margin-top"
      <p>4/5 Green Leaf Café at the Burnaby Location is a testament to korean-japanese fusion and offers some of the best quality dishes I have tried in a while. Though a relatively big space, they have offset it with cozy decor, offering a comfortable ambience I thoroughly enjoyed.</p> 
      <p>Green Leaf Café is known for their aburi sushi, and I ordered salmon oshi and unagi oshi, both of which were amazing! It was extremely rich and dense and perfect to share with friends. Their mentaiko linguine was the stand-out as I love creamy pasta. Their shrimp was cooked to perfection and the noodles were deliciously chewy. The tornado omlette rice reminded me of meals I’ve had in Japan and as you cut into it, the stew comes out all at once. Price point was fair for the quality they offer and I would come back here again!</p>
      <p>This would be the perfect date setting or an intimate night with friends to enjoy a great meal together. A must!!</p>
  </div>

  <div id="The Lunch Lady">
      <h1>The Lunch Lady</h1>
      <img src="./images/Iqqq.jpeg" style="width:100%;max-width:1000px" class="w3-margin-top" />
      <p>4.5/5 The Lunch Lady, located on Commercial Drive, has seen continuous lines outside its doors despite the pandemic’s impact on customer dining habits. Upon first glance, The Lunch Lady bursts with vibrance, featuring street art outside its location, not unlike the streets of Saigon. The restaurant itself is chic and modern, boasting sleek decor with a bar that rivals its competitors.
      <p>Its story began in Saigon, where Mrs. Nguyen Thi Thanh has served many global customers in her food stall, scoring an acclaimed review from the late Anthony Bourdain himself, calling her “The Lunch Lady”. After traveling to Vietnam in 2012, Michel Tran teamed up with Mrs. Nguyen to bring her flavours to North America, and the food is absolutely incredible.
      <p>I ordered the Pho-Bò (Beef Noodle Soup) which was packed with flavour in its broth from the first bite. I paired it with their shrimp vermicelli rolls which gave it fresh notes. Next up was the Steak Luc Lac, their take on a classic rib-eye steak served with fresh vegetables and a fried egg. The Bún Thit Nuong Chà Giò (pork skewers & vermicelli) however, was my favourite as it continued to burst with new flavour in every bite. Words can’t explain how much I loved it!
      <p>Cool down here and enjoy Mrs. Nguyen Thi Thanh’s world famous recipes with a refreshing pint of beer!</p>
  </div>

  <div id="Hokkaido Ramen Santouka">
      <h1>Hokkaido Ramen Santouka</h1>
      <img src="./images/final.jpeg" style="width:100%;max-width:1000px" class="w3-margin-top" />
      <p>5/5 What do you crave most on a rainy night? For me, a hot bowl of noodle soup does the trick and Hokkaido Ramen Santouka provides the perfect fix for a cold winter night.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore</p>
      <p>I remember coming here extremely tired after a day full of classes, and the rain outside was pouring just like a typical day here in Vancouver. My friend and I were looking for a ramen place on Broadway and so, after a quick google search, we found ourselves here. Like many restaurants along West Broadway, the interior is small and comfortable, providing a bustling atmosphere perfect for conversations with family and friends, reflecting Hokkaido Ramen Santouka’s statement on their website “Especially Made for Families”.</p>
      <p>Ramen Santouka originated from Asahikawa, Hokkaido, Japan when Hitoshi Hatanaka told his family that he was going to make delicious ramen, and that, he did. I ordered the shio ramen combo which was amazing. They make their soup handmade from scratch at each individual location and the broth was extremely rich and not too salty, which I highly appreciated. The pork itself was also tender and cooked perfectly- when paired with the rice donburi, it was more than enough to get full as I doubted the size of the ramen bowl at first, which was wrong!</p>
      <p>The price point was affordable and for the quality itself, worth every penny spent. 
        Come here on a cold day or honestly, whenever to fill your stomach with happiness!</p>
  </div>
 
<!-- Community Container -->
<div class="w3-container" id="community" style="padding-bottom:32px;">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">COMMUNITY</span></h5>
    <p>Sign up to follow us along our CHOW DOWN JOURNEY!</p>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="number" placeholder="Email" required name="People"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Restaurant recommendations" required name="date" value="2020-11-16T20:00"></p>
      <p><button class="w3-button w3-black" type="submit">SEND MESSAGE</button></p>
    </form>
  </div>
</div>

<!-- End page content -->
</div>

<!-- Footer -->
<footer class="w3-center w3-light-grey w3-padding-48 w3-large">
  <p>Sponsored by <a href="https://shehacks.ca/">SheHacks</a></p>
</footer>

<script>
// Tabbed Menu
function openMenu(evt, menuName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("menu");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" w3-dark-grey", "");
  }
  document.getElementById(menuName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-dark-grey";
}
document.getElementById("myLink").click();
</script>

</body>
</html>

