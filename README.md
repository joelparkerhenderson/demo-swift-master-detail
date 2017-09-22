# Demo Swift Master Detail

This demonstration shows:

  * The [Swift](http://swift.org) programming language with
    [Apple](http://apple.com)
    [Xcode](https://developer.apple.com/xcode/)
    [iOS](http://www.apple.com/ios/)

  * How to create a [master-detail interface](https://en.wikipedia.org/wiki/Master%E2%80%93detail_interface). 

  * The interface can create an item, open an item, and delete an item. 

This README describes how to create the demo.


## Start

To use this demo, you can clone this repo, or you can use this README to create your own project.

If you clone this repo, then be aware that there are multiple git branches, so pick the one you want.

  * swift-4-xcode-9: Swift version 4, Xcode version 9, iOS version 11.

  * swift-3-xcode-8: Swift version 3, Xcode version 8, iOS version 10.


## Create the project

Launch Xcode and create a new Xcode project. 

  * We call ours "Demo Swift Master Detail" and we choose the template "Master-Detail Application".

  * [Help](doc/setup/create_a_new_xcode_project.md)
  

## How to use the app

Create an item.

  * Tap the button "+" which creates a master item.

  * The master item automatically shows the creation date and time.

Open an item.

  * Tap the item, which slides open to show the detail view of the item.

  * To return to the master list, tap the upper left label "Master".

Delete an item.

  * Tap-press the item and drag left, which slides open the label "Delete".

  * Tap the label "Delete".


## Tracking

* Package: demo_swift_master_detail
* Version: 3.0.0
* Created: 2016-04-09
* Updated: 2017-09-22
* License: BSD, GPL, MIT
* Contact: Joel Parker Henderson (http://joelparkerhenderson.com)
