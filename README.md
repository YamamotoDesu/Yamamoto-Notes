# Yamamoto-Notes

## Tool List
* [iTerm](https://iterm2.com/)
* [Oh My Zsh](https://ohmyz.sh/)
* [Gifox](https://gifox.io/) 
* Skitch
* Soucetree
* ServiceStation
* [Chrome](https://www.google.co.jp/chrome/?brand=AGAK&gclid=CjwKCAiA24SPBhB0EiwAjBgkhiXZh863fMju_CqqkkS3di-DvHSkZqgRdEj-0ut9ny8NWT5_Te27hxoCQigQAvD_BwE&gclsrc=aw.ds)
    * [Talend API Tester](https://chrome.google.com/webstore/detail/talend-api-tester-free-ed/aejoelaoggembcahagimdiliamlcdmfm?hl=ja)
* Xcode
 ※ [archive](https://stackoverflow.com/questions/10335747/how-to-download-xcode-dmg-or-xip-file)
* [Android Studio](https://developer.android.com/studio)
  ※ [archive](https://developer.android.com/studio/archive?hl=ja)
* Alfred
* Mockoon
* [SF Symbols](https://developer.apple.com/sf-symbols/)

## Bookmark
*  [Check-CSS-Supported-Browser](https://caniuse.com/)
*  [Check-Color-Contrast](https://color.adobe.com/ja/create/color-contrast-analyzer)
*  [Dummy-Api-And-Server](https://httpbin.org/)
*  [Create-UIColor](https://www.uicolor.io/)
*  [Check-Other-Apps](https://mobbin.design/browse/ios/apps)

## Check-List
* iOS New Feature Checklist
* [iPhone Device 
resolution](https://qiita.com/tomohisaota/items/f8857d01f328e34fb551)
* [Android Device resolution](https://en.wikipedia.org/wiki/Comparison_of_high-definition_smartphone_displays)

## Xcode env
*  Shortcut

*  Snippets
https://gist.github.com/YamamotoDesu

## iOS Development
* ### [ScrollableView vs UICollectionView vs UITableView](https://github.com/jrasmusson/ios-professional-course/tree/main/Bankey/5-Scrollable-ViewControllers)
  * ScrollableView(Common)  
     <details open>
         <summary>Pros</summary> 
            <ol type="1">
               <li>Makes anything scrollable</li>
               <li>Minimalist</li>
               <li>Full controll</li>
               <li>Good for long pages</li>
            </ol>
      </details>
     <details open>
         <summary>Cons</summary> 
            <ol type="1">
               <li>Can't easily reload</li>
               <li>No built in affordances   
                  (i.e. pull to reload)
               </li>
               <li>Full controll</li>
               <li>Auto Layout more complext</li>
            </ol>
      </details>

  * UICollectionView(Rare)
     <details open>
         <summary>Pros</summary> 
            <ol type="1">
               <li>Customizable layoutse</li>
               <li>Multi-column scrollable</li>
               <li>Can dynamically change layout</li>
               <li>Good for photos in a grid</li>
            </ol>
     </details>
     <details open>
         <summary>Cons</summary> 
            <ol type="1">
               <li>More complex</li>
               <li>Often overkill</li>
            </ol>
      </details>
      
   * UITableView(All the time)
     <details open>
         <summary>Pros</summary> 
            <ol type="1">
               <li>Heighly performant
                   (reuseIdentifiers)
               </li>
               <li>Many affordances built in
                   (header, footer, sections)</li>
               <li>Perfext for single column lists</li>
            </ol>
     </details>
     <details open>
         <summary>Cons</summary> 
            <ol type="1">
               <li>Hard to do complext non-single column layouts </li>
            </ol>
      </details>   
      
  
  
