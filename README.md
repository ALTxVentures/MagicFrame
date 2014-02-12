MagicFrame
===========

iFrame redirect with child title support and query string and hash pass-through.

If url is set to 'abc.com' and incoming address is 'http://originaldomain.com/hello.html?q=test&testmode=true#test', the iFrame will take visitors to 'http://abc.com?q=test&testmode=true#test' and sets the title to that of abc.com.
