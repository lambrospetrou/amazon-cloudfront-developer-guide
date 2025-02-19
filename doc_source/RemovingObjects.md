# Removing content so CloudFront won’t distribute it<a name="RemovingObjects"></a>

You can remove files from your origin that you no longer want to be included in your CloudFront distribution\. However, CloudFront will continue to show viewers content from the edge cache until the files expire\. 

If you want to remove a file right away, you must do one of the following:
+ **Invalidate the file\.** For more information, see [Invalidating files](Invalidation.md)\.
+ **Use file versioning\.** When you use versioning, different versions of a file have different names that you can use in your CloudFront distribution, to change which file is returned to viewers\. For more information, see [Updating existing files using versioned file names](UpdatingExistingObjects.md#ReplacingObjects)\.