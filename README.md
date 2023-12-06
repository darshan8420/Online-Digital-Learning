# Digitalcourse App

It is a basic flutter Application. It provides the lessons and lectures about UI/UX development, Mobile App development, Graphichs design and others( Features are listed in below). Moreover,
a messaging i.e Chatting feature, has been integrated additional with the application.

# Features
- UI/UX learning
- Mobile App Development
- Graphic Design
- Web Developemnt
- Social Media
- Internet Course
- English writing/speaking
- Painting
- Photography 

# Screen-Shots
![](assets/icons/Frame%2037.png)
![](assets/icons/Frame%2038.png)

# Quick Start
This is a normal Flutter App. You should follow the instructions in the [Offical documentation](https://docs.flutter.dev/get-started/install). 

# Modularization Structure
# Project Structure

- assets                        
  - icons                        
  - categories                  

- lib                  
  - core                   
    - errors               
    - services             
    - utils                
  - src
    - features
         -  account.presentation.pages.account     
         -  chat.presentation.pages.chat           
         -  course                                 
              - data                               
              - domain                             
              - presentation                       
                   - bloc                          
                   - pages   
    - theme                 
    - widget                



# Built with 🛠

. [Cupertino Icons](https://pub.dev/packages/cupertino_icons) - Default icons asset for Cupertino widgets based on Apple styled icons

. [Flutter Lints](https://pub.dev/packages/flutter_lints) - Recommended lints for Flutter apps, packages, and plugins to encourage good coding practices.

. [Flutter SVG](https://pub.dev/packages/flutter_svg) - An SVG rendering and widget library for Flutter, which allows painting and displaying Scalable Vector Graphics 

. [Carousel Slider](https://pub.dev/packages/carousel_slider) - A carousel slider widget, support infinite scroll and custom child widget.

. [Readmore](https://pub.dev/packages/readmore) - A Flutter package than allow expand and collapse text dynamically

. [Cached Network Image](https://pub.dev/packages/cached_network_image) - Flutter library to load and cache network images. Can also be used with placeholder and error widgets.

. [Flutter Custom Tab Bar](https://pub.dev/packages/flutter_custom_tab_bar) - Custom tab bar

. [Equatable](https://pub.dev/packages/equatable) - A Dart package that helps to implement value based equality without needing to explicitly override == and hashCode.

. [Dartz](https://pub.dev/packages/dartz) -  Purify your Dart code using efficient immutable data structures, monads, lenses and other FP tools.

. [Http](https://pub.dev/packages/http) - A composable, multi-platform, Future-based API for HTTP requests.

. [Flutter BLoC](https://pub.dev/packages/flutter_bloc) - Built to be used with the bloc state management package.

. [Get It](https://pub.dev/packages/get_it) - Simple direct Service Locator that allows to decouple and access the interface from a concrete implementation 


# How to run the App

1. Clone this project.
2. Open with your favorite tools editor.
3. Run Pub get on each module sequentially starting from dependencies, core, shared, and your root project to generated pubspec.lock file.
4. But before you running that, make sure go to core module first using cd command. For example cd libraries and then cd core. Then you can run this command: flutter packages pub run build_runner build --delete-conflicting-outputs.
Run the App using this or this. Enjoy your App!.


