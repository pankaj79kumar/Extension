# Extension
= Mediawiki Extension =

= Sync Mediawiki Categories =

This is MediaWiki extension to specify that Sync the all article from particular Categories from one Mediawiki to Other.

== Installation ==

* Download and place the files in a directory called SyncCategories in your extensions/ folder.

* Add the following code at the bottom of your <tt>LocalSettings.php</tt>:

<source lang="php">
wfLoadExtension( 'SyncCategories' );
</source>


== Job Queue ==

Job should sit in the queue and wait to run.


