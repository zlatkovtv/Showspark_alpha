#Known issues

FIXED for back: 1. Statusbars and back functionality for wizard pages doesnt work. Home-> Login pages are connected with events that set them, but the wizard pages dont. Check js file for more.

2. Create login-default.html page (home), extract content of index.html to login-default, keep only top level element in index.
3. I can swipe panel open in wizard pages, which is not intended behavior. Fix with page callback methods (pageOnInit).

FIXED 4. !! Make cards better

5. Refresher is working on css side but not js side. Resolve issue
6. BUG !! Cant swipe out panel on swipable tabs
FIXED 7. !! wizards-result
FIXED 8. Input values and object build for query
9. tabbar isnt hiding on scroll on second tab
10. fix rss pages back button to be goToTabs and not exitPrompt
FIXED 1. Fix startup e.g. splashscreen
2. Side panel clear and favourites + fb db
!!! 3. tab view search functionality for finding a movie or tv series
5. Loaders on callback ajax methods FIX POSITION ON RESULTVIEW
!!! 6. Template for movie detail view
7. black bar when tutorial is opened from sidepanel
8. resultview bug changing movies

#Library edits
1. .swiper-slide .preloader edited in material.min.css
2. .deeppurple edited in material.min.css