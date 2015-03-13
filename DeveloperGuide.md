# 1.0 Technologies and tools used #
  * Flex Builder
  * Actionscript 3
  * Flare Visualization Toolkit

# 2.0 Building the project (with Flare libraries) #

  1. Install Flex builder SDK/Flex trial version
> 2. Create a project.
http://individual.utoronto.ca/i_wa_wong/capture.JPG
> 3. Download the feature downloads for the developers.
> 4. Unzip the folder and copy and paste the src folder into the src folder of the newly created project.
> 5. Click the run button in the Flex builder SDK/Flex trial version to build the project.
> 6. You should then be able to see your application from your bin-debug folder loaded into your defaulted browser.

# 3.0 Important security settings needed for the application built #
Due to the [security changes](http://www.adobe.com/devnet/flash/articles/fplayer8_security_print.html) of Flash 7 onwards, in order to allow the built flash application to fetch data remotely, it is necessary to [change the current directory](http://www.macromedia.com/support/documentation/en/flashplayer/help/settings_manager04.html) where the built application locates to “local trusted”. The file bin-debug of a project is of sandbox type "local-trusted" by default once the project is created.

# 4.0 Useful Links #
|Links|Description|
|:----|:----------|
|[Flex Builder Trial](http://www.adobe.com/cfusion/entitlement/index.cfm?e=flex3email)|Download link for the trial version of Flex Builder|
|[Flex SDK open source](http://opensource.adobe.com/wiki/display/flexsdk/Flex+SDK;jsessionid=222F21CF33EEE1FEFA9CCEE0FA24E1BD)|Download link for the open source version of Flex SDK|
|[Flare API](http://flare.prefuse.org/api/)|The API of the flare libraries.|
|[Flex API](http://livedocs.adobe.com/flex/3/langref/index.html)|The API of Flex and Flash built-in libraries|
|[Flare Help Forum](http://sourceforge.net/forum/forum.php?forum_id=757572)|A very useful forum for any help in developing web-based application using actionscript 3 and flare|