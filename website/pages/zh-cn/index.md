---
layout: "ssg-theme-astro/layouts/main.astro"
tag: ""
title: 'Imperial Soup 皇帝湯 - Best Food Today'
favicon: "favicon.ico"
logo: "logo.webp"
primaryColor: "#CEB841" # logo color
secondaryColor: "#ffffff"
primaryColorScheme: "light" # dark | light
secondaryColorScheme: "light"
dataGlfCuidOrderOnline: ""
dataGlfRuidOrderOnline: ""
dataGlfCuidTableReservation: ""
dataGlfRuidTableReservation: ""
orderOnlineLink: "#" # For multiple restaurants, please leave this blank.
tableReservationLink: "#"
tel: "510-893-2288" # For multiple restaurants, please leave this blank.

# banner:
#   text: 
#     - boldText: "🥳 Special Offer"
#     - text: "15 PC of Head On Shrimp + 1 Free Soda + Choose a Free Item:"
#     - smText: "Steam Rice (10 oz cup) / Garlic Noodles (10 oz cup) / Cajun Fries
#               (10 oz cup) only $13.50. Available Monday to Friday, 12 PM to 3
#               PM."
#     - text: ""
#   # add more text...
#   textColor: "#ffffff"
#   bgColor: "#FF2D2F"
#   bgOpacity: "1" # 0~1

# header
header:
  logoSize: 55
  textAfterLogo: 
    text: ""
    size: 16
    color: ""
  bgColor: "#3A2A1B"
  bgOpacity: "0.9" # 0~1
  menuTextColor: "#ffffff"
  menu:
    - { text: "首頁", link: "/zh-cn" }
    - { text: "菜品展示", link: "#gallery" }
    - { text: "關於我們", link: "#about-us" }
    - { text: "聯繫我們", link: "#contact-us" }
    - { text: "English", link: "/" }
  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: "" 
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: false
  telTextColor: "#ffffff"
  addOtherBtn: true
  otherBtn1InsteadText: "查看菜單 / 在線訂餐" 
  otherBtn1Href: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=752ba859-e555-4d56-94c7-1855de8f1c0c"
  otherBtn2InsteadText: "预订餐位" 
  otherBtn2Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu/reservation?restaurant_uid=752ba859-e555-4d56-94c7-1855de8f1c0c&reservation=true"


sections:
# Hero
  - type: "hero" 
    id: ""
    height: "90" # Conditionally use only when sectionType is imgBg
    sectionType: "imgBg" # video | imgWithText | imgBg
    bgVideoType: "" # youtube | vimeo | gjw
    bgVideoId: ""
    bgImg: "ImperialSoup.webp"
    bgImgAlt: 'Imperial Soup 皇帝湯 - Best Food Today'
    bgColor: "#000"
    bgOpacity: "0.5" # 0~1
    title: 
      - 'Imperial Soup 皇帝湯 - Best Food Today'
    titleColor: "#ffffff"
    description: 
      - '奧克蘭的中國美食'
    descriptionColor: "#ffffff"

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: "查看菜單 / 在線訂餐" 
    addTableReservationBtn: false
    tableReservationBtnInsteadText: "预订餐位"
    showOtherBtn: true
    btn1Text: "查看菜單 / 在線訂餐" 
    btn1Href: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=752ba859-e555-4d56-94c7-1855de8f1c0c" 
    btn2Text: "预订餐位"
    btn2Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu/reservation?restaurant_uid=752ba859-e555-4d56-94c7-1855de8f1c0c&reservation=true" 

    bannerImg: ""
    imgAlt: ""
    imgPosition: "" # imgLeft | imgRight
    bannerMarginTopMobile: 96
    imgRounded: "" # sm | md | lg | xl | 2xl | 3xl | full
    extraStyleToTheImage: ""
   
    bottomRounded: "" # sm | md | lg | xl | 2xl | 3xl | full
    # bottomInfo: "We offer Takeout"

# # Video
#   - type: "video"
#     id: ""
#     title: 
#       - "A Corner of Tradition and Flavor"
#     description: 
#       - "From the heart of Newark, CA, Crabby Crabby Restaurant is a corner where tradition meets flavor. Every corner of our restaurant is infused with authenticity, from the décor to every bite we serve." 
#     videoType: "vimeo" # vimeo | gjw | youtube
#     videoId: 
#       - "963713403"
#       - "917321697"
#     isOnlyDisplayOnMobile: false

# Gallery  
  - type: "gallery"
    id: "gallery"
    mode: 1 # 1 - 3
    bgImg: ""
    bgImgAlt: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Imperial Soup 皇帝湯 菜品展示"
    titleColor: "#000000"
    description: 
      - "地道中國美食，等你來品嚐"
    descriptionColor: "#333333"
    folderPath: "gallery"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full


# textBlock 
  - type: "textBlock" 
    id: "about-us"
    bgImg: ""
    bgImgAlt: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "關於我們"
    titleColor: "#000000"
    description: 
      - "Imperial Soup 皇帝湯是一家位於奧克蘭的美味餐廳，專營正宗特色蒸湯。"
      - "我們的湯品不僅味道鮮美，還具有藥用價值。根據不同的季節，我們提供多種湯品選擇，以滿足您在不同方面的健康需求。"
      - "我們不僅供應禦湯料理，還有其他亞洲美食。如果您有任何疑問，歡迎隨時與我們聯繫！我們會盡快回覆您!"
    descriptionColor: "#000000"

# # feature - 2
#   - type: "feature" 
#     id: "contact-us"
#     height: "100" # Conditionally use only when sectionType is imgBg
#     sectionType: "imgWithText" # video | imgWithText | imgBg
#     bgVideoType: "" # youtube | vimeo | gjw
#     bgVideoId: ""
#     bgImg: ""
#     bgImgAlt: ""
#     bgColor: ""
#     bgOpacity: "" # 0~1
#     title: 
#       - "Store 1: Kearny St"
#     titleColor: "#000000"
#     description: 
#       - "Opening Hours: Mon-Sat 10:30 AM-7:00 PM"
#     descriptionColor: "#000000"
#     # title2: 
#     #   - "A Corner of Tradition and Flavor"
#     # title2Color: "#000000"
#     # description2: 
#     #   - "From the heart of Newark, CA, Crabby Crabby Restaurant is a corner where tradition meets flavor. Every corner of our restaurant is infused with authenticity, from the décor to every bite we serve."
#     #   # - text: "We serve Imperial Soup dishes plus other Asian dishes. Feel free to message us about inquiries! We'll get back to you as soon as we can!"
#     # description2Color: "#000000"
#     # title2: 
#     #   - "Committed to the Community"
#     # title2Color: "#000000"
#     # description2: 
#     #   - "We are proud to be an active part of the Newark, CA community. Through special events, collaborations with local venues and participation in community initiatives, Crabby Crabby Restaurant seeks to strengthen the ties that bind us together."
#     # description2Color: "#000000"
#     isTextAlignCenter: false

#     addOrderOnlineBtn: false
#     orderOnlineBtnInsteadText: "See MENU & Order"
#     addTableReservationBtn: false
#     tableReservationBtnInsteadText: ""
#     showOtherBtn: true
#     btn1Text: "Order online from Kearny St store" 
#     btn1Href: "https://onlineorder.bestfood.today/Restaurant/details/MTAwNDA=" 
#     btn2Text: "" 
#     btn2Href: "" 

#     bannerImg: ""
#     imgAlt: ""
#     imgPosition: "" # imgLeft | imgRight
    
#     map: true
#     url: "https://maps.app.goo.gl/nZ57LDJrofANer8J6"
#     iframeUrl: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d394.10234978168285!2d-122.4046165!3d37.7942861!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085808b1948e55b%3A0xcb3994bcd586810e!2sHon&#39;s%20Wun-Tun%20House!5e0!3m2!1sen!2sus!4v1722231832722!5m2!1sen!2sus"
#     addTelBtn: true
#     tel: "4154333966"
#     telInsteadText: "Call: (415) 433-3966"
#     getDirectionBtnInsteadText: ""
    
    
#     bottomRounded: "" # sm | md | lg | xl | 2xl | 3xl | full (only for background)


# # feature - 3
#   - type: "feature" 
#     id: ""
#     height: "100" # Conditionally use only when sectionType is imgBg
#     sectionType: "imgWithText" # video | imgWithText | imgBg
#     bgVideoType: "" # youtube | vimeo | gjw
#     bgVideoId: ""
#     bgImg: ""
#     bgImgAlt: ""
#     bgColor: ""
#     bgOpacity: "" # 0~1
#     title: 
#       - "Store 2 : Washington St"
#     titleColor: "#000000"
#     description: 
#       - "Opening Hours: Mon-Fri 8:30 AM-8:00 PM, Sat-Sun 9:00 AM-8:30 PM"
#     descriptionColor: "#000000"

#     addOrderOnlineBtn: false
#     orderOnlineBtnInsteadText: "See MENU & Order"
#     addTableReservationBtn: false
#     tableReservationBtnInsteadText: ""
#     showOtherBtn: true
#     btn1Text: "Order online from Washington St" 
#     btn1Href: "https://onlineorder.bestfood.today/Restaurant/details/MTAwNDE=" 
#     btn2Text: "" 
#     btn2Href: "" 

#     bannerImg: ""
#     imgAlt: ""
#     imgPosition: "" # imgLeft | imgRight

#     map: true
#     url: "https://maps.app.goo.gl/HDDb5yFih4S8TmDe7"
#     iframeUrl: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d197.0491990412703!2d-122.4063506!3d37.7950269!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085815e4be59617%3A0x87622e118f7e38a2!2sHon%E2%80%99s%20Wun-Tun%20House!5e0!3m2!1sen!2sjp!4v1722232541079!5m2!1sen!2sjp"
#     addTelBtn: true
#     tel: "4153973232"
#     telInsteadText: "Call: (415) 397-3232"
#     tel2: "4153972887"
#     tel2InsteadText: "Call: (415) 397-2887"
#     getDirectionBtnInsteadText: ""
   
#     bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

# textBlock - Information
  - type: "textBlock" 
    id: ""
    bgImg: "/gallery/Imperial Soup Dish14.webp"
    bgImgAlt: "Crabby Crabby Newark - Best Food Today"
    bgColor: "#000"
    bgOpacity: "0.4" # 0~1
    title: 
      - "新功能！在線訂餐"
    titleColor: "#ffffff"
    description: 
      - "現在支援線上訂單自取。只要告訴我們您想要的菜餚，我們會​​盡快準備好。所有訂單都由我們手動確認。您可以即時查看您的食物何時準備好。訂單狀態會即時更新，您可以在螢幕上查看您的食物何時可以取走。"
    descriptionColor: "#ffffff"
  
# map  
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/gHferfbrQsJXDHNX9"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3163.2010723950107!2d-122.05385532436703!3d37.55032622505781!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808fbf25977c4139%3A0x65a0766c424ad6dc!2sCrabby%20Crabby%20Newark!5e0!3m2!1sen!2sjp!4v1721832800644!5m2!1sen!2sjp"
    addTelBtn: true
    getDirectionBtnInsteadText: "帶我去餐廳"
    telInsteadText: "tel: (510) 893-2288"
 
  # - type: "modal"
  #   bgColor: "#333"
  #   bgOpacity: "0.1" # 0~1
  #   title: 
  #     - "🥳 Special Offers"
  #   titleColor: "#FF2D2F"
  #   titleSize: 24
  #   description: ""
  #   descriptionColor: ""
  #   descriptionSize: 16
  #   imgName: "offer.png"
  #   imgAlt: "🥳 Special Offer 15 PC of Head On Shrimp + 1 Free Soda + Choose a Free Item: Steam Rice (10 oz cup) / Garlic Noodles (10 oz cup) / Cajun Fries (10 oz cup) only $13.50. Available Monday to Friday, 12 PM to 3 PM."
  #   buttonText: "Order Now!"

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: ""
  bgImgAlt: ""
  bgColor: "#000000"
  bgOpacity: "0.9" # 0~1
  # openingHours: 
  #   - "Monday to Friday: Lunch 11:30 AM to 3:00 PM, Dinner 5:00 PM to 9:00 PM"
  #   - "Saturday and Sunday: 12:00 PM to 9:00 PM"

  isLogo: true
  logoSize: 60
  menu:
    - { text: "首頁", link: "/zh-cn" }
    - { text: "菜品展示", link: "#gallery" }
    - { text: "關於我們", link: "#about-us" }
    - { text: "聯繫我們", link: "#contact-us" }
    - { text: "English", link: "/" }
  FB: false
  FBLink: ""
  IG: false
  IGLink: ""
  X: false
  XLink: ""
  youtube: false
  youtubeLink: ""
  yelp: false
  yelpLink: ""
  paymentMethod: "" #,alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal

  seo:
    metaDescription: "欢迎在线订购外卖或预订餐位。歡迎到奥克兰的Imperial Soup 皇帝汤 - Best Food Today，品嚐我們為您精心準備的正宗特色蒸湯。"
    keywords: ""
    img: ""
    thisPageUrl: "https://www.imperialsoupoakland.com/zh-cn"
    locale: "zh_CN" # zh_TW | zh_CN

---
