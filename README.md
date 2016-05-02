# info3180-project3

<h2>Part 2 of Project at https://github.com/Davyan/info3180-project4<h2>
Wishlist Application built with Flask and Angular

<h2>API description</h2>

<li>POST /signup</li>
<p>Requires name, email, password and confirmation</p>
<p>Returns created user</p>

<li>POST /login</li>
<p>Required email and password</p>
<p>Returns user and token</p>

<li>POST /wishlist/(user_id)</li>
<p>Requires "AuthToken: (token)" header to contain a token for this user"</p>
<p>Adds an item to the wishlist</p>

<li>GET /wishlist/(user_id)</li>
<p>Returns a users wishlist</li>

<li>GET /wishlist/(user_id)/(item_id)</li>
<p>Returns an item from a user's wishlist</p>

<li>DELETE /wishlist/(user_id)/(item_id)</li>
<p>Requires "AuthToken: (token)" header to contain a token for this user"</p>
<p>Returns an item from a user's wishlist</p>

<li>GET /wishlist</li>
<p>Returns all users</p>

<li>POST /scrape</li>
<p>Takes a URL and returns possible thumbnails and title if possible</p>
