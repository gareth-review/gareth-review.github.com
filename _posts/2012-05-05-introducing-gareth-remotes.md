---
layout: post
title: "Introducing Gareth: Remotes"
categories: progress
---
The next important fundamental component is "Remotes". Every project in Gareth can have an unlimited set of remotes. Every remote belongs to a single user.

A remote essentially maps to a remote inside the git repo. To contribute to a project a user sets up their own public repository; This repo may be on GitHub, BitBucket, Gitorious, a personal server, or even in a repository management system setup by the organization that setup the Gareth instance. After setting this repo up the user creates a new remote in Gareth and points the url of that remote to a read-only url for their public git repo. Whenever they push changes to their public repo someone tells Gareth to fetch the commits that have been added to that remote and then turn those new commits into sets for review.

## Screenshots

<ul class="thumbnails" id="gallery" data-toggle="modal-gallery" data-target="#modal-gallery">
	<li class="span3">
		<div class="thumbnail">
			<a href="/screenshots/remotes-view-2012-05-04.png" title="Remotes list" rel="gallery">
				<img alt="" src="/screenshot-thumbs/remotes-view-2012-05-04.png">
			</a>
			<div class="caption">
				<h5>Remotes list</h5>
			</div>
		</div>
	</li>
	<li class="span3">
		<div class="thumbnail">
			<a href="/screenshots/remote-view-2012-05-04.png" title="Remote page" rel="gallery">
				<img alt="" src="/screenshot-thumbs/remote-view-2012-05-04.png">
			</a>
			<div class="caption">
				<h5>Remote page</h5>
			</div>
		</div>
	</li>
</ul>