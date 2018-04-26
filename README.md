# How to disabled out side click on bootstrap model



<h1>Basic Bootstrap model HTML code</h1>
<p>Make sure that you have import bootstrap library . Mease bootstrap.css or bootstrap.min.css And bootstrap.js or bootstrap.min.js</p>


# Using HTML CODE

<h4>You have to add this two data attributes in the trigger button.</h4>

<pre><code> data-backdrop="static" data-keyboard="false"  </code></pre>

# Using jQuery CODE

<h4>You have to add same as below script in your model script.</h4>

<pre><code> $('#myModal').modal({backdrop: 'static', keyboard: false});  </code></pre>
