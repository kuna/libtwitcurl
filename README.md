libtwitcurl - twitter library for cpp
original from https://code.google.com/p/twitcurl/
edited by kuna

- changed few codes cause it didn't work.. (need http protocol state)
- future plan: add pic.twitter.com upload feature
- 140127: added upload_with_media function
- 140128:
 * caution! - uploadPictureBase64 method wasn't tested, so use uploadPictureRaw method. and please make sure that std::string uploadPicture argument should be already encoded with UTF8 if you want to use Unicode status message!