<p align="center">
	<img src="/Assets/ZWalletLogo.png" width="500"/>
</p>

## Awesome App For Saving Time.

ZWallet is an electronic wallet application designed to solve problems during banking or transactional activities, such as transfers and others. With this app any transaction to be as easy as the touch of a finger. you can enjoy a clean, faster, more practical, and safer payment method

### Tech in Use
In this project, we use several technology to implemented in this app
1. VIPER Design Pattern
2. Swift 5 
3. NetFox
4. Cocoapods
5. KingFisher
6. Moya

## Screenshots

These are some of the User Interface of ZWallet Application

[<img src="/Assets/Login.png" width="250"/>](Login)
[<img src="/Assets/Home.png" width="250"/>](Home)
[<img src="/Assets/TopUp.png" width="250"/>](TopUp)
[<img src="/Assets/TransferReceiver.png" width="250"/>](TransferReceiver)
[<img src="/Assets/TransferDetail.png" width="250"/>](TransferDetail)

## How to Install
1. Clone this repository <br />
First, simply clone this repository using basic git command
	- Create a directory in your local storage
	- Type `git clone`
	```
	$ git clone https://github.com/adhyfahmyh/zwallet-viper.git
	```
2. Install dependency using [**Cocoapods**](https://cocoapods.org/), type `pod install`
3. Go to App folder, then open **ZWallet.xcworkspace** using XCODE
4. RUN

## Usage

### VIPER
1. View
	The responsibility of the view is to send the user actions to the presenter and shows whatever the presenter tells it
2. Interactor
	The Interactor is a class that mediates between the presenter and the data. It takes direction from the presenter
3. Presenter
	Its responsibility is to get the data from the interactor on user actions and after getting data from the interactor, it sends it to the view to show it. It also asks the router/wireframe for navigation
4. Entity
	The Entity contains basic model objects used by the Interactor
5. Router
	The Router handles navigation between screens/ It has all navigation logic for describing which screens are to be shown when