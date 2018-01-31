# Break Upsource

This is an example which shows how upsource (IMO wrongly) shows obsolete code in reviews. Which I find annoying sometimes.

# Branches

 * branch `first` contains somes changes
 * branch `second` removes some parts which were changed in `first`
 * `second` is then merged to `first`

In this case upsource still shows obsolete changes from `first` which were already overwritten by `second`.

# How to see that

To see that create a review on branch `first`.
