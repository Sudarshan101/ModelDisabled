# How to disabled out side click on bootstrap model



<h1>Basic Bootstrap model HTML code</h1>
<p>Make sure that you have import bootstrap library . Mease bootstrap.css or bootstrap.min.css And bootstrap.js or bootstrap.min.js</p>

# Button trigger modal

<pre><code><button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#myModal">Launch demo modal</button></code></pre>


# Modal Box

<pre><code>	<div class="modal fade" id="myModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
	  <div class="modal-dialog" role="document">
		<div class="modal-content">
		  <div class="modal-header">
			<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
			<h4 class="modal-title" id="myModalLabel">Modal title</h4>
		  </div>
		  <div class="modal-body">
			...
		  </div>
		  <div class="modal-footer">
			<button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
			<button type="button" class="btn btn-primary">Save changes</button>
		  </div>
		</div>
	  </div>
	</div>
</code></pre>

# Using HTML CODE

<h4>You have to add this two data attributes in the button.</h4>

<pre><code> data-backdrop="static" data-keyboard="false"  </code></pre>

# Using jQuery CODE

<h4>You have to add same as below script in your model script.</h4>

<pre><code> $('#myModal').modal({backdrop: 'static', keyboard: false});  </code></pre>
