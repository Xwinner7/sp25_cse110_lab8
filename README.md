# Lab8 - Fetch API & ServiceWorkers
### Team: Xiuwen Zhu & Christina W
1) Deployed GitHub Pages URL: https://xwinner7.github.io/sp25_cse110_lab8/
2) How are graceful degradation and service workers related?
- By ensuring that core functionality remains avabilable even when the network connectivity is weak or failed, service workers support graceful degradation. They accomplish such by intercepting network requests and serving cached reponses when live data cannot be fetched. Because of this fallback mechanism, the program can continue to function in a restricted capacity while still being usable. Service workers increase the resilience of applications by enhancing load performance and offering offline support. They smoothly improve the experience by providing access to live content after full connectivity has been restored. The concepts of progressive enhancement and graceful degradation are reflected in this balance between online enhancement and offline fallback, which guarantees a dependable user experience under a range of network conditions.
3) pwa.png
![PWA](pwa.png)
