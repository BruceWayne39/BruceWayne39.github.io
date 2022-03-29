<html lang="en" id="facebook" class=""><head><meta charset="utf-8"><meta name="referrer" content="origin-when-crossorigin" id="meta_referrer"><script nonce="">window._cstart=+new Date();</script><script nonce="">function envFlush(a){function b(b){for(var c in a)b[c]=a[c]}window.requireLazy?window.requireLazy(["Env"],b):(window.Env=window.Env||{},b(window.Env))}envFlush({"ajaxpipe_token":"AXizRns7Te4OhmJ-vxE","timeslice_heartbeat_config":{"pollIntervalMs":33,"idleGapThresholdMs":60,"ignoredTimesliceNames":{"requestAnimationFrame":true,"Event listenHandler mousemove":true,"Event listenHandler mouseover":true,"Event listenHandler mouseout":true,"Event listenHandler scroll":true},"isHeartbeatEnabled":true,"isArtilleryOn":false},"shouldLogCounters":true,"timeslice_categories":{"react_render":true,"reflow":true},"sample_continuation_stacktraces":true,"dom_mutation_flag":true,"gk_requirelazy_mem":true,"gk_instrument_object_url":true,"stack_trace_limit":30,"timesliceBufferSize":5000,"show_invariant_decoder":false,"compat_iframe_token":"AQ7_MQrGcvSRGth_E_4","isCQuick":false});</script><style nonce=""></style><script nonce="">__DEV__=0;CavalryLogger=window.CavalryLogger||function(a){this.lid=a,this.transition=!1,this.metric_collected=!1,this.is_detailed_profiler=!1,this.instrumentation_started=!1,this.pagelet_metrics={},this.events={},this.ongoing_watch={},this.values={t_cstart:window._cstart},this.piggy_values={},this.bootloader_metrics={},this.resource_to_pagelet_mapping={},this.initializeInstrumentation&&this.initializeInstrumentation()},CavalryLogger.prototype.setIsDetailedProfiler=function(a){this.is_detailed_profiler=a;return this},CavalryLogger.prototype.setTTIEvent=function(a){this.tti_event=a;return this},CavalryLogger.prototype.setValue=function(a,b,c,d){d=d?this.piggy_values:this.values;(typeof d[a]==="undefined"||c)&&(d[a]=b);return this},CavalryLogger.prototype.getLastTtiValue=function(){return this.lastTtiValue},CavalryLogger.prototype.setTimeStamp=CavalryLogger.prototype.setTimeStamp||function(a,b,c,d){this.mark(a);var e=this.values.t_cstart||this.values.t_start;e=d?e+d:CavalryLogger.now();this.setValue(a,e,b,c);this.tti_event&&a==this.tti_event&&(this.lastTtiValue=e,this.setTimeStamp("t_tti",b));return this},CavalryLogger.prototype.mark=typeof console==="object"&&console.timeStamp?function(a){console.timeStamp(a)}:function(){},CavalryLogger.prototype.addPiggyback=function(a,b){this.piggy_values[a]=b;return this},CavalryLogger.instances={},CavalryLogger.id=0,CavalryLogger.getInstance=function(a){typeof a==="undefined"&&(a=CavalryLogger.id);CavalryLogger.instances[a]||(CavalryLogger.instances[a]=new CavalryLogger(a));return CavalryLogger.instances[a]},CavalryLogger.setPageID=function(a){if(CavalryLogger.id===0){var b=CavalryLogger.getInstance();CavalryLogger.instances[a]=b;CavalryLogger.instances[a].lid=a;delete CavalryLogger.instances[0]}CavalryLogger.id=a},CavalryLogger.now=function(){return window.performance&&performance.timing&&performance.timing.navigationStart&&performance.now?performance.now()+performance.timing.navigationStart:new Date().getTime()},CavalryLogger.prototype.measureResources=function(){},CavalryLogger.prototype.profileEarlyResources=function(){},CavalryLogger.getBootloaderMetricsFromAllLoggers=function(){},CavalryLogger.start_js=function(){},CavalryLogger.start_js_script=function(){},CavalryLogger.done_js=function(){};CavalryLogger.getInstance().setTTIEvent("t_domcontent");CavalryLogger.prototype.measureResources=function(a,b){if(!this.log_resources)return;var c="bootload/"+a.name;if(this.bootloader_metrics[c]!==void 0||this.ongoing_watch[c]!==void 0)return;var d=CavalryLogger.now();this.ongoing_watch[c]=d;"start_"+c in this.bootloader_metrics||(this.bootloader_metrics["start_"+c]=d);b&&!("tag_"+c in this.bootloader_metrics)&&(this.bootloader_metrics["tag_"+c]=b);if(a.type==="js"){c="js_exec/"+a.name;this.ongoing_watch[c]=d}},CavalryLogger.prototype.stopWatch=function(a){if(this.ongoing_watch[a]){var b=CavalryLogger.now(),c=b-this.ongoing_watch[a];this.bootloader_metrics[a]=c;var d=this.piggy_values;a.indexOf("bootload")===0&&(d.t_resource_download||(d.t_resource_download=0),d.resources_downloaded||(d.resources_downloaded=0),d.t_resource_download+=c,d.resources_downloaded+=1,d["tag_"+a]=="_EF_"&&(d.t_pagelet_cssload_early_resources=b));delete this.ongoing_watch[a]}return this},CavalryLogger.getBootloaderMetricsFromAllLoggers=function(){var a={};Object.values(window.CavalryLogger.instances).forEach(function(b){b.bootloader_metrics&&Object.assign(a,b.bootloader_metrics)});return a},CavalryLogger.start_js=function(a){for(var b=0;b<a.length;++b)CavalryLogger.getInstance().stopWatch("js_exec/"+a[b])},CavalryLogger.start_js_script=function(a){if(!a||!a.dataset)return;CavalryLogger.start_js([a.dataset.bootloaderHash||a.dataset.bootloaderHashClient])},CavalryLogger.done_js=function(a){for(var b=0;b<a.length;++b)CavalryLogger.getInstance().stopWatch("bootload/"+a[b])},CavalryLogger.prototype.profileEarlyResources=function(a){for(var b=0;b<a.length;b++)this.measureResources({name:a[b][0],type:a[b][1]?"js":""},"_EF_")};CavalryLogger.getInstance().log_resources=true;CavalryLogger.getInstance().setIsDetailedProfiler(true);window.CavalryLogger&&CavalryLogger.getInstance().setTimeStamp("t_start");</script><noscript><meta http-equiv="refresh" content="0; URL=/?_fb_noscript=1" /></noscript><link rel="manifest" id="MANIFEST_LINK" href="/data/manifest/" crossorigin="use-credentials"><title id="pageTitle">Facebook – log in or sign up</title><meta property="og:site_name" content="Facebook"><meta property="og:url" content="https://www.facebook.com/"><meta property="og:image" content="https://www.facebook.com/images/fb_icon_325x325.png"><meta property="og:locale" content="en_GB"><link rel="alternate" media="only screen and (max-width: 640px)" href="https://m.facebook.com/"><link rel="alternate" media="handheld" href="https://m.facebook.com/"><meta name="description" content="Log in to Facebook to start sharing and connecting with your friends, family and people you know."><script type="application/ld+json" nonce="">{"\u0040context":"http:\/\/schema.org","\u0040type":"WebSite","name":"Facebook","url":"https:\/\/en-gb.facebook.com\/"}</script><link rel="canonical" href="https://www.facebook.com/"><link rel="shortcut icon" href="https://static.xx.fbcdn.net/rsrc.php/yb/r/hLRJ1GG_y0J.ico"><link type="text/css" rel="stylesheet" href="https://static.xx.fbcdn.net/rsrc.php/v3/yL/l/0,cross/RGwypa6I2jS.css?_nc_x=Ij3Wp8lg5Kz" data-bootloader-hash="6XWCS9s" crossorigin="anonymous">
<link type="text/css" rel="stylesheet" href="https://static.xx.fbcdn.net/rsrc.php/v3/yo/l/0,cross/Fc91FO1H-Zk.css?_nc_x=Ij3Wp8lg5Kz" data-bootloader-hash="XGDA5to" crossorigin="anonymous">
<link type="text/css" rel="stylesheet" href="https://static.xx.fbcdn.net/rsrc.php/v3/yg/l/0,cross/e5HhDlJHlk1.css?_nc_x=Ij3Wp8lg5Kz" data-bootloader-hash="T/eaVKH" crossorigin="anonymous">
<link type="text/css" rel="stylesheet" href="https://static.xx.fbcdn.net/rsrc.php/v3/yD/l/0,cross/JYql2bxfGFO.css?_nc_x=Ij3Wp8lg5Kz" data-bootloader-hash="27iTcKo" crossorigin="anonymous">
<link type="text/css" rel="stylesheet" href="https://static.xx.fbcdn.net/rsrc.php/v3/yk/l/0,cross/sPcFrnaRncH.css?_nc_x=Ij3Wp8lg5Kz" data-bootloader-hash="vi/i3HE" crossorigin="anonymous">
<link type="text/css" rel="stylesheet" href="https://static.xx.fbcdn.net/rsrc.php/v3/yF/l/0,cross/nG7XmC3cZWM.css?_nc_x=Ij3Wp8lg5Kz" data-bootloader-hash="Yo2UzOh" crossorigin="anonymous">
<script src="https://static.xx.fbcdn.net/rsrc.php/v3/yE/r/vInFLPaxeb4.js?_nc_x=Ij3Wp8lg5Kz" data-bootloader-hash="bpk/MKX" crossorigin="anonymous" nonce=""></script>
<script nonce="">requireLazy(["HasteSupportData"],function(m){m.handle({"clpData":{"1814852":{"r":1},"1838142":{"r":1,"s":1},"1949898":{"r":1},"1848815":{"r":10000,"s":1},"1744178":{"r":1,"s":1}},"gkxData":{"5241":{"result":true,"hash":"AT7o1bCQPGpf3ShEMXs"},"676837":{"result":false,"hash":"AT4N8wBZA8ctCdHwZ9M"},"708253":{"result":false,"hash":"AT5n4hBL3YTMnQWtXh4"},"996940":{"result":false,"hash":"AT7opYuEGy3sjG1axr8"},"1224637":{"result":false,"hash":"AT7JRluWxuwDm3XzUx0"},"1263340":{"result":false,"hash":"AT5bwizWgDaFQudmK3E"},"676920":{"result":true,"hash":"AT497IX4gOFG8gZeM8M"},"1073500":{"result":false,"hash":"AT7aJmfnqWyioxOOlEE"},"1167394":{"result":false,"hash":"AT7BpN-tlUPwbIIFBfA"},"1857581":{"result":false,"hash":"AT5yTxGMp6le0PAtbjM"},"2772":{"result":false,"hash":"AT5Eu244WIce7iwqyxY"},"3752":{"result":false,"hash":"AT6eS5UTkkMp_xbPXN0"},"3831":{"result":false,"hash":"AT4W23lQ0XxAZniMet8"},"4075":{"result":false,"hash":"AT4_ZQi0sTjSt-RxhYU"},"676838":{"result":false,"hash":"AT6nN1ehT9yq-2q60Ec"},"1217157":{"result":false,"hash":"AT6B7YmllOsArnK6Ag4"},"1554827":{"result":false,"hash":"AT7zueGLhGo0cT5xSVY"},"1738486":{"result":false,"hash":"AT4cX37oQco6DwhUJr0"}},"qplData":{"7758":{"r":1}}})});requireLazy(["TimeSliceImpl","ServerJS"],function(TimeSlice,ServerJS){(new ServerJS()).handle({"define":[["URLFragmentPreludeConfig",[],{"hashtagRedirect":true,"fragBlacklist":["nonce","access_token","oauth_token","xs","checkpoint_data","code"]},137],["CometPersistQueryParams",[],{"relative":{},"domain":{}},6231],["CookieDomain",[],{"domain":"facebook.com"},6421],["BootloaderConfig",[],{"deferBootloads":false,"jsRetries":[200,500],"jsRetryAbortNum":2,"jsRetryAbortTime":5,"silentDups":false,"hypStep4":false,"phdOn":false,"btCutoffIndex":3045},329],["CSSLoaderConfig",[],{"timeout":5000,"modulePrefix":"BLCSS:","loadEventSupported":true},619],["CookieCoreConfig",[],{"c_user":{"s":"None"},"cppo":{"t":86400,"s":"None"},"dpr":{"t":604800,"s":"None"},"fbl_ci":{"t":31536000,"s":"None"},"fbl_cs":{"t":31536000,"s":"None"},"fbl_st":{"t":31536000,"s":"Strict"},"i_user":{"s":"None"},"locale":{"t":604800,"s":"None"},"m_pixel_ratio":{"t":604800,"s":"None"},"noscript":{"s":"None"},"presence":{"t":2592000,"s":"None"},"sfau":{"s":"None"},"usida":{"s":"None"},"vpd":{"t":5184000,"s":"Lax"},"wd":{"t":604800,"s":"Lax"},"x-referer":{"s":"None"},"x-src":{"t":1,"s":"None"}},2104],["CurrentCommunityInitialData",[],{},490],["CurrentEnvironment",[],{"facebookdotcom":true,"messengerdotcom":false,"workplacedotcom":false,"instagramdotcom":false},827],["CurrentUserInitialData",[],{"ACCOUNT_ID":"0","USER_ID":"0","NAME":"","SHORT_NAME":null,"IS_BUSINESS_PERSON_ACCOUNT":false,"HAS_SECONDARY_BUSINESS_PERSON":false,"IS_FACEBOOK_WORK_ACCOUNT":false,"IS_MESSENGER_ONLY_USER":false,"IS_DEACTIVATED_ALLOWED_ON_MESSENGER":false,"IS_MESSENGER_CALL_GUEST_USER":false,"IS_WORK_MESSENGER_CALL_GUEST_USER":false,"APP_ID":"256281040558","IS_BUSINESS_DOMAIN":false},270],["DTSGInitialData",[],{},258],["ISB",[],{},330],["LSD",[],{"token":"AVqkJE7N2-s"},323],["ServerNonce",[],{"ServerNonce":"yzvkMwrB1-JmAlNodTlc3X"},141],["SiteData",[],{"server_revision":1005260860,"client_revision":1005260860,"tier":"","push_phase":"C3","pkg_cohort":"BP:DEFAULT","haste_session":"19080.BP:DEFAULT.2.0.0.0.","pr":1,"haste_site":"www","manifest_base_uri":"https:\/\/static.xx.fbcdn.net","manifest_origin":null,"be_one_ahead":false,"is_rtl":false,"is_comet":false,"is_experimental_tier":false,"is_jit_warmed_up":true,"hsi":"7080497951380118007-0","semr_host_bucket":"5","bl_hash_version":2,"skip_rd_bl":true,"comet_env":0,"wbloks_env":false,"spin":4,"__spin_r":1005260860,"__spin_b":"trunk","__spin_t":1648556895,"vip":"31.13.83.36"},317],["SprinkleConfig",[],{"param_name":"jazoest","version":2,"should_randomize":false},2111],["UserAgentData",[],{"browserArchitecture":"64","browserFullVersion":"99.0.4844.82","browserMinorVersion":0,"browserName":"Chrome","browserVersion":99,"deviceName":"Unknown","engineName":"WebKit","engineVersion":"537.36","platformArchitecture":"64","platformName":"Windows","platformVersion":"10","platformFullVersion":"10"},527],["PromiseUsePolyfillSetImmediateGK",[],{"www_always_use_polyfill_setimmediate":false},2190],["KSConfig",[],{"killed":{"__set":["MOBILIZER_SELF_SERVE_OWNERSHIP_RESOLVER","MLHUB_FLOW_AUTOREFRESH_SEARCH","NEKO_DISABLE_CREATE_FOR_SAP","EO_DISABLE_SYSTEM_SERIAL_NUMBER_FREE_TYPING_IN_CPE_NON_CLIENT","MOBILITY_KILL_OLD_VISIBILITY_POSITION_SETTING","WORKPLACE_DISPLAY_TEXT_EVIDENCE_REPORTING","BUSINESS_INVITE_FLOW_WITH_SELLER_PROFILE","BUY_AT_UI_LINE_DELETE","BUSINESS_GRAPH_SETTING_APP_ASSIGNED_USERS_NEW_API","BUSINESS_GRAPH_SETTING_BU_ASSIGNED_USERS_NEW_API","BUSINESS_GRAPH_SETTING_ESG_ASSIGNED_USERS_NEW_API","BUSINESS_GRAPH_SETTING_PRODUCT_CATALOG_ASSIGNED_USERS_NEW_API","BUSINESS_GRAPH_SETTING_SESG_ASSIGNED_USERS_NEW_API","BUSINESS_GRAPH_SETTING_WABA_ASSIGNED_USERS_NEW_API","ADS_PLACEMENT_FIX_PUBLISHER_PLATFORMS_MUTATION","FORCE_FETCH_BOOSTED_COMPONENT_AFTER_ADS_CREATION","VIDEO_DIMENSIONS_FROM_PLAYER_IN_UPLOAD_DIALOG","SNIVY_GROUP_BY_EVENT_TRACE_ID_AND_NAME","ADS_STORE_VISITS_METRICS_DEPRECATION","DYNAMIC_ADS_SET_CATALOG_AND_PRODUCT_SET_TOGETHER","AD_DRAFT_ENABLE_SYNCRHONOUS_FRAGMENT_VALIDATION","NEKO_ENABLE_RESET_SAP_FOR_CREATE_AD_SET_CONTEXTUAL","SEPARATE_MESSAGING_COMACTIVITY_PAGE_PERMS","LAB_NET_NEW_UI_RELEASE","POCKET_MONSTERS_CREATE","POCKET_MONSTERS_DELETE","SRT_BANZAI_SRT_CORE_LOGGER","SRT_BANZAI_SRT_MAIN_LOGGER","WORKPLACE_PLATFORM_SECURE_APPS_MAILBOXES","POCKET_MONSTERS_UPDATE_NAME","IC_DISABLE_MERGE_TOOL_FEED_CHECK_FOR_REPLACE_SCHEDULE","ADS_EPD_IMPACTED_ADVERTISER_MIGRATE_XCONTROLLER","RECRUITING_CANDIDATE_PORTAL_ACCOUNT_DELETION_CARD"]},"ko":{"__set":["8H4bQmEiuLT","3OsLvnSHNTt","1G7wJ6bJt9K","9NpkGYwzrPG","3oh5Mw86USj","8NAceEy9JZo","7FOIzos6XJX","rf8JEPGgOi","4j36SVzvP3w","4NSq3ZC4ScE","53gCxKq281G","3yzzwBY7Npj","1onzIv0jH6H","8PlKuowafe8","1ntjZ2zgf03","4SIH2GRVX5W","2dhqRnqXGLQ","2WgiNOrHVuC","amKHb4Cw4WI","5mNEXob0nTj","8rDvN9vWdAK","9cL5o2kjfZo","5BdzWGmfvrA","DDZhogI19W","acrJTh9WGdp","1oOE64fL4wO","9Gd8qgRxn8z","MPMaqnqZ9c","5XCz1h9Iaw3","7r6mSP7ofr2","6DGPLrRdyts","aWxCyi1sEC7","9kCSDzzr8fu"]}},2580],["JSErrorLoggingConfig",[],{"appId":256281040558,"extra":[],"reportInterval":50,"sampleWeight":null,"sampleWeightKey":"__jssesw","projectBlocklist":[]},2776],["DataStoreConfig",[],{"expandoKey":"__FB_STORE","useExpando":true},2915],["CookieCoreLoggingConfig",[],{"maximumIgnorableStallMs":16.67,"sampleRate":9.7e-5,"sampleRateClassic":1.0e-10,"sampleRateFastStale":1.0e-8},3401],["ImmediateImplementationExperiments",[],{"prefer_message_channel":true},3419],["DTSGInitData",[],{"token":"","async_get_token":""},3515],["UriNeedRawQuerySVConfig",[],{"uris":["dms.netmng.com","doubleclick.net","r.msn.com","watchit.sky.com","graphite.instagram.com","www.kfc.co.th","learn.pantheon.io","www.landmarkshops.in","www.ncl.com","s0.wp.com","www.tatacliq.com","bs.serving-sys.com","kohls.com","lazada.co.th","xg4ken.com","technopark.ru","officedepot.com.mx","bestbuy.com.mx","booking.com","nibio.no"]},3871],["InitialCookieConsent",[],{"deferCookies":false,"initialConsent":{"__set":[1,2]},"noCookies":false,"shouldShowCookieBanner":false},4328],["TrustedTypesConfig",[],{"useTrustedTypes":false,"reportOnly":false},4548],["WebConnectionClassServerGuess",[],{"connectionClass":"GOOD"},4705],["CometAltpayJsSdkIframeAllowedDomains",[],{"allowed_domains":["https:\/\/live.adyen.com","https:\/\/integration-facebook.payu.in","https:\/\/facebook.payulatam.com","https:\/\/secure.payu.com","https:\/\/facebook.dlocal.com","https:\/\/buy2.boku.com"]},4920],["BootloaderEndpointConfig",[],{"debugNoBatching":false,"endpointURI":"https:\/\/www.facebook.com\/ajax\/bootloader-endpoint\/"},5094],["CookieConsentIFrameConfig",[],{"consent_param":"FQAREhIA.ARY8-_PsMXQQoiy2MKdq2caP2PMxUUH9bms7c5CmSs7-3_bB","allowlisted_iframes":[]},5540],["BigPipeExperiments",[],{"link_images_to_pagelets":false,"enable_bigpipe_plugins":false},907],["IntlVariationHoldout",[],{"disable_variation":false},6533],["AsyncRequestConfig",[],{"retryOnNetworkError":"1","useFetchStreamAjaxPipeTransport":false},328],["FbtQTOverrides",[],{"overrides":{}},551],["FbtResultGK",[],{"shouldReturnFbtResult":true,"inlineMode":"NO_INLINE"},876],["IntlPhonologicalRules",[],{"meta":{"\/_B\/":"([.,!?\\s]|^)","\/_E\/":"([.,!?\\s]|$)"},"patterns":{"\/\u0001(.*)('|&#039;)s\u0001(?:'|&#039;)s(.*)\/":"\u0001$1$2s\u0001$3","\/_\u0001([^\u0001]*)\u0001\/":"javascript"}},1496],["IntlViewerContext",[],{"GENDER":3,"regionalLocale":null},772],["NumberFormatConfig",[],{"decimalSeparator":".","numberDelimiter":",","minDigitsForThousandsSeparator":4,"standardDecimalPatternInfo":{"primaryGroupSize":3,"secondaryGroupSize":3},"numberingSystemData":null},54],["SessionNameConfig",[],{"seed":"2kKI"},757],["ZeroCategoryHeader",[],{},1127],["ZeroRewriteRules",[],{"rewrite_rules":{},"whitelist":{"\/hr\/r":1,"\/hr\/p":1,"\/zero\/unsupported_browser\/":1,"\/zero\/policy\/optin":1,"\/zero\/optin\/write\/":1,"\/zero\/optin\/legal\/":1,"\/zero\/optin\/free\/":1,"\/about\/privacy\/":1,"\/about\/privacy\/update\/":1,"\/privacy\/explanation\/":1,"\/zero\/toggle\/welcome\/":1,"\/zero\/toggle\/nux\/":1,"\/zero\/toggle\/settings\/":1,"\/fup\/interstitial\/":1,"\/work\/landing":1,"\/work\/login\/":1,"\/work\/email\/":1,"\/ai.php":1,"\/js_dialog_resources\/dialog_descriptions_android.json":0,"\/connect\/jsdialog\/MPlatformAppInvitesJSDialog\/":0,"\/connect\/jsdialog\/MPlatformOAuthShimJSDialog\/":0,"\/connect\/jsdialog\/MPlatformLikeJSDialog\/":0,"\/qp\/interstitial\/":1,"\/qp\/action\/redirect\/":1,"\/qp\/action\/close\/":1,"\/zero\/support\/ineligible\/":1,"\/zero_balance_redirect\/":1,"\/zero_balance_redirect":1,"\/zero_balance_redirect\/l\/":1,"\/l.php":1,"\/lsr.php":1,"\/ajax\/dtsg\/":1,"\/checkpoint\/block\/":1,"\/exitdsite":1,"\/zero\/balance\/pixel\/":1,"\/zero\/balance\/":1,"\/zero\/balance\/carrier_landing\/":1,"\/zero\/flex\/logging\/":1,"\/tr":1,"\/tr\/":1,"\/sem_campaigns\/sem_pixel_test\/":1,"\/bookmarks\/flyout\/body\/":1,"\/zero\/subno\/":1,"\/confirmemail.php":1,"\/policies\/":1,"\/mobile\/internetdotorg\/classifier\/":1,"\/zero\/dogfooding":1,"\/xti.php":1,"\/zero\/fblite\/config\/":1,"\/hr\/zsh\/wc\/":1,"\/ajax\/bootloader-endpoint\/":1,"\/mobile\/zero\/carrier_page\/":1,"\/mobile\/zero\/carrier_page\/education_page\/":1,"\/mobile\/zero\/carrier_page\/feature_switch\/":1,"\/mobile\/zero\/carrier_page\/settings_page\/":1,"\/aloha_check_build":1,"\/upsell\/zbd\/softnudge\/":1,"\/mobile\/zero\/af_transition\/":1,"\/mobile\/zero\/af_transition\/action\/":1,"\/mobile\/zero\/freemium\/":1,"\/mobile\/zero\/freemium\/redirect\/":1,"\/mobile\/zero\/freemium\/zero_fup\/":1,"\/privacy\/policy\/":1,"\/privacy\/center\/":1,"\/data\/manifest\/":1,"\/4oh4.php":1,"\/autologin.php":1,"\/birthday_help.php":1,"\/checkpoint\/":1,"\/contact-importer\/":1,"\/cr.php":1,"\/legal\/terms\/":1,"\/login.php":1,"\/login\/":1,"\/mobile\/account\/":1,"\/n\/":1,"\/remote_test_device\/":1,"\/upsell\/buy\/":1,"\/upsell\/buyconfirm\/":1,"\/upsell\/buyresult\/":1,"\/upsell\/promos\/":1,"\/upsell\/continue\/":1,"\/upsell\/h\/promos\/":1,"\/upsell\/loan\/learnmore\/":1,"\/upsell\/purchase\/":1,"\/upsell\/promos\/upgrade\/":1,"\/upsell\/buy_redirect\/":1,"\/upsell\/loan\/buyconfirm\/":1,"\/upsell\/loan\/buy\/":1,"\/upsell\/sms\/":1,"\/wap\/a\/channel\/reconnect.php":1,"\/wap\/a\/nux\/wizard\/nav.php":1,"\/wap\/appreg.php":1,"\/wap\/birthday_help.php":1,"\/wap\/c.php":1,"\/wap\/confirmemail.php":1,"\/wap\/cr.php":1,"\/wap\/login.php":1,"\/wap\/r.php":1,"\/zero\/datapolicy":1,"\/a\/timezone.php":1,"\/a\/bz":1,"\/bz\/reliability":1,"\/r.php":1,"\/mr\/":1,"\/reg\/":1,"\/registration\/log\/":1,"\/terms\/":1,"\/f123\/":1,"\/expert\/":1,"\/experts\/":1,"\/terms\/index.php":1,"\/terms.php":1,"\/srr\/":1,"\/msite\/redirect\/":1,"\/fbs\/pixel\/":1,"\/contactpoint\/preconfirmation\/":1,"\/contactpoint\/cliff\/":1,"\/contactpoint\/confirm\/submit\/":1,"\/contactpoint\/confirmed\/":1,"\/contactpoint\/login\/":1,"\/preconfirmation\/contactpoint_change\/":1,"\/help\/contact\/":1,"\/survey\/":1,"\/upsell\/loyaltytopup\/accept\/":1,"\/settings\/":1,"\/lite\/":1,"\/zero_status_update\/":1,"\/operator_store\/":1,"\/upsell\/":1,"\/wifiauth\/login\/":1}},1478],["IntlNumberTypeConfig",[],{"impl":"if (n === 1) { return IntlVariations.NUMBER_ONE; } else { return IntlVariations.NUMBER_OTHER; }"},3405],["ServerTimeData",[],{"serverTime":1648556895967,"timeOfRequestStart":1648556895924.7,"timeOfResponseStart":1648556895924.7},5943],["AnalyticsCoreData",[],{"device_id":"$^|AcbcoNWykbXn_rhmcJeAWJP5nq15QikRBVpAqUww0U4_hcv4KRLJlpPStAJxc6q4MixjVWEFfhB3rGnpdd2EOYuvY7B2|fd.Aca53cEPihnH5x5QcaHqgEHGHCur-6CypOH72aJELqiISq1nopCQ_SkeR5qM8C7bY2zJ3lEWhvBXPDjI1FU7PGT9","app_id":"256281040558","enable_bladerunner":false,"enable_ack":true,"push_phase":"C3","enable_observer":false,"enable_dataloss_timer":false,"enable_fallback_for_br":true},5237],["cr:696703",[],{"__rc":[null,"Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:708886",["EventProfilerImpl"],{"__rc":["EventProfilerImpl","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:717822",["TimeSliceImpl"],{"__rc":["TimeSliceImpl","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:806696",["clearTimeoutBlue"],{"__rc":["clearTimeoutBlue","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:807042",["setTimeoutBlue"],{"__rc":["setTimeoutBlue","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:896462",["setIntervalAcrossTransitionsBlue"],{"__rc":["setIntervalAcrossTransitionsBlue","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:986633",["setTimeoutAcrossTransitionsBlue"],{"__rc":["setTimeoutAcrossTransitionsBlue","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:1003267",["clearIntervalBlue"],{"__rc":["clearIntervalBlue","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:1183579",["InlineFbtResultImpl"],{"__rc":["InlineFbtResultImpl","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:925100",["RunBlue"],{"__rc":["RunBlue","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:729414",["VisualCompletion"],{"__rc":["VisualCompletion","Aa3ELVUrsA6b0xTun6r3YwjqBmSK6QE_QQeDYDgfeZdWf_gLZj9OpN4t_Ekh99uOJ-AmMdrw15hDzBVbzh1WtIx4"]},-1],["cr:1094907",[],{"__rc":[null,"Aa3QRBC7W7iGODp6Mqbqek_EPVWdHlO4V9kQ8u7bqwLj1tW_aG4P_2wKa5Sz0QuLIv57eLbRdpy84oA2n0_jan0"]},-1],["EventConfig",[],{"sampling":{"bandwidth":0,"play":0,"playing":0,"progress":0,"pause":0,"ended":0,"seeked":0,"seeking":0,"waiting":0,"loadedmetadata":0,"canplay":0,"selectionchange":0,"change":0,"timeupdate":0,"adaptation":0,"focus":0,"blur":0,"load":0,"error":0,"message":0,"abort":0,"storage":0,"scroll":200000,"mousemove":20000,"mouseover":10000,"mouseout":10000,"mousewheel":1,"MSPointerMove":10000,"keydown":0.1,"click":0.02,"mouseup":0.02,"__100ms":0.001,"__default":5000,"__min":100,"__interactionDefault":200,"__eventDefault":100000},"page_sampling_boost":1,"interaction_regexes":{},"interaction_boost":{},"event_types":{},"manual_instrumentation":false,"profile_eager_execution":false,"disable_heuristic":true,"disable_event_profiler":false},1726],["AdsInterfacesSessionConfig",[],{},2393],["IntlCurrentLocale",[],{"code":"en_GB"},5954],["USIDMetadata",[],{"browser_id":"?","tab_id":"","page_id":"Pr9ian3835r4h","transition_id":0,"version":6},5888],["cr:686",[],{"__rc":[null,"Aa0NlrmSSfTQ-gXOvWrnh7gHhPG3283yEviZL_-jG7zqu63gqXn5rfjXGUTwNmAcFLh4IYrOZE2mq3gr5vnEuoER"]},-1],["cr:1984081",[],{"__rc":[null,"Aa1xyH5qOKw4NI7cxHtCJeL7uBM1o0ylk-tjpn99X5DV8vpzpZn7yzv8ttmclFeufvaI56wc-1NhApXlxlKDtbt0ASl7"]},-1]],"require":[["markJSEnabled"],["lowerDomain"],["URLFragmentPrelude"],["Primer"],["BigPipe"],["Bootloader"],["TimeSlice"],["AsyncRequest"],["BanzaiScuba_DEPRECATED"],["VisualCompletionGating"],["FbtLogging"],["IntlQtEventFalcoEvent"],["RequireDeferredReference","unblock",[],[["AsyncRequest","BanzaiScuba_DEPRECATED","VisualCompletionGating","FbtLogging","IntlQtEventFalcoEvent"],"sd"]],["RequireDeferredReference","unblock",[],[["AsyncRequest","BanzaiScuba_DEPRECATED","VisualCompletionGating","FbtLogging","IntlQtEventFalcoEvent"],"css"]]]});});</script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yK/r/28qx5chKB37.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yK/r/28qx5chKB37.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="SJt9b58"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3ij9m4/y2/l/en_GB/IRVL8mwJYmC.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3ij9m4/y2/l/en_GB/IRVL8mwJYmC.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="WW8fqVn"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yU/r/BwlkRv7B4IH.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yU/r/BwlkRv7B4IH.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="00Aws6K"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/y6/r/04MM-wufnk2.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/y6/r/04MM-wufnk2.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="foxoXrn"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yZ/r/Jhvid9xmsdT.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yZ/r/Jhvid9xmsdT.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="i4ulAqS"></script><link rel="stylesheet" type="text/css" href="data:text/css; charset=utf-8,%23bootloader_P_mr5VE{height:42px;}.bootloader_P_mr5VE{display:block!important;}"><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yu/r/XaPDIOxwUYb.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yu/r/XaPDIOxwUYb.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="1Rv/+Xz"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yW/r/6wpkzLV7sfC.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yW/r/6wpkzLV7sfC.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="TDbeFtl"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3i3674/yI/l/en_GB/54_EE3F38vK.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3i3674/yI/l/en_GB/54_EE3F38vK.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="7xieS14"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3iCwx4/y8/l/en_GB/HiZbSfs0RcK.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3iCwx4/y8/l/en_GB/HiZbSfs0RcK.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="ZjF9HpG"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yr/r/yYxqF7t4UC4.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yr/r/yYxqF7t4UC4.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="VJBByUf"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yY/r/dhKWcQzymk8.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yY/r/dhKWcQzymk8.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="h3A96RM"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/yW4xJArCb1U.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/yW4xJArCb1U.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="DArYdIE"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yZ/r/x4Eyp9nQ1uk.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yZ/r/x4Eyp9nQ1uk.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="CGkH4FY"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yj/r/ylQZGjtoTZS.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yj/r/ylQZGjtoTZS.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="VYX+Uc1"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/y5/r/ruBIfAyOqFt.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/y5/r/ruBIfAyOqFt.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="dtBHfNn"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yX/r/xOJs33xJ5Fd.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yX/r/xOJs33xJ5Fd.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="CBQ4zUl"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yU/r/wIj-E6Prut5.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yU/r/wIj-E6Prut5.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="2CbDRJL"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/KWY7Edb5_DT.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/KWY7Edb5_DT.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="FEt5GzN"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3iX3c4/yG/l/en_GB/3ni-w8nVeg8.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3iX3c4/yG/l/en_GB/3ni-w8nVeg8.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="RSfm84C"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yt/r/NiMhI8TA3eX.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yt/r/NiMhI8TA3eX.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="xO06VLK"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/y9/r/ugD21mPGNBo.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/y9/r/ugD21mPGNBo.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="XVtAULI"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yN/r/g2e1F4SS2Pz.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yN/r/g2e1F4SS2Pz.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="45g2zGz"></script><link href="https://static.xx.fbcdn.net/rsrc.php/v3/yE/r/oufs3Uw-tgc.js?_nc_x=Ij3Wp8lg5Kz" rel="preload" as="script" crossorigin="anonymous"><script src="https://static.xx.fbcdn.net/rsrc.php/v3/yE/r/oufs3Uw-tgc.js?_nc_x=Ij3Wp8lg5Kz" async="" crossorigin="anonymous" data-bootloader-hash-client="wBnHkAZ"></script></head><body class="fbIndex UIPage_LoggedOut _-kb _605a b_c3pyn-ahh chrome webkit win x1 Locale_en_GB cores-gte4 _19_u hasAXNavMenubar" dir="ltr">
<script type="text/javascript" language="javascript">
//<![CDATA[
var bd_nd_B937DB990D1548698380D65CF906E308 = 
{
    /// [etl] urls[100][0] = [status,scan, version, url]
    /// status = {added, alias?, ready, skipped}
    /// reuse urls. need version
    /// (list) bd_nd_B937DB990D1548698380D65CF906E308.links[][0] = [urls.index, urls.version, link ?, anchor?]
    ///             delete item from bd_nd_B937DB990D1548698380D65CF906E308.links after engine response & icon
    ICON_GREEN      : "/F9CD80F3-B79B-49AB-AD16-6F61BFFFC81B/netdefender/ls/icons/ok.png",
    ICON_YELLOW     : "/F9CD80F3-B79B-49AB-AD16-6F61BFFFC81B/netdefender/ls/icons/warn.png",
    ICON_RED        : "/F9CD80F3-B79B-49AB-AD16-6F61BFFFC81B/netdefender/ls/icons/nok.png",

    TOOLTIP_GREEN   : "/F9CD80F3-B79B-49AB-AD16-6F61BFFFC81B/netdefender/ls/tooltips/ok.png",
    TOOLTIP_YELLOW  : "/F9CD80F3-B79B-49AB-AD16-6F61BFFFC81B/netdefender/ls/tooltips/warn.png",
    TOOLTIP_RED     : "/F9CD80F3-B79B-49AB-AD16-6F61BFFFC81B/netdefender/ls/tooltips/nok.png",

    STATUS_ADDED    : 1,
    STATUS_ALIAS    : 2,
    STATUS_READY    : 3,
    STATUS_SKIPPED  : 4,

    STATUS_GREEN    : 1,
    STATUS_YELLOW   : 2,
    STATUS_RED      : 3,

    HEADER_NAME     : "BDNDLS_F9CD80F3B79B49ABAD166F61BFFFC81B",
    ANCHOR_PREFIX   : "bd_nd_B937DB990D1548698380D65CF906E308_anchor_",
    ICON_PREFIX     : "bd_nd_B937DB990D1548698380D65CF906E308_icon_",

    title           : "Web Protection by <strong>Bitdefender</strong>",
    green_title     : "This page is safe",
    green_content   : "We could not find any suspect elements on this page.",
    yellow_title    : "This page might be unsafe",
    yellow_content  : "We detected elements that may harm your computer.",
    red_title       : "This page is unsafe",
    red_content     : "We detected elements that may harm your computer.",
    fraud_link      : "https://trafficlight.bitdefender.com/info?url={URL}&language=en_US",

    iconGREEN       : null,
    iconYELLOW      : null,
    iconRED         : null,

    tooltipGREEN    : null,
    tooltipYELLOW   : null,
    tooltipRED      : null,

    fInit           : false,
    links           : null,
    console_log     : null,

    isGoogle        : /^https:\/\/www\.google\..{1,5}\/search\?.+/.test(window.location.href),

    isPageOK : function() {
        if (typeof(window.top) != 'object') {
            if (window.parent != window) {
                return false; } }
        return true;
    },

    canEmbed : function() {
        var rv = -1; 
        if (navigator.appName != 'Microsoft Internet Explorer') {
            return true; }
        var ua = navigator.userAgent;
        var re = new RegExp("MSIE ([0-9]{1,}[\.0-9]{0,})");
        if (re.exec(ua) != null) {
            rv = parseFloat(RegExp.$1); }
        if (rv >= 8.0) {
            return true; }		
        return false;
    },

    init: function () {
        if (bd_nd_B937DB990D1548698380D65CF906E308.fInit) {
            return; }
        bd_nd_B937DB990D1548698380D65CF906E308.fInit = true;
        bd_nd_B937DB990D1548698380D65CF906E308.iconGREEN = new String();
        bd_nd_B937DB990D1548698380D65CF906E308.iconYELLOW = new String();
        bd_nd_B937DB990D1548698380D65CF906E308.iconRED = new String();

        if (bd_nd_B937DB990D1548698380D65CF906E308.canEmbed()) {
            bd_nd_B937DB990D1548698380D65CF906E308.iconGREEN = "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAABGdBTUEAALGPC/xhBQAAA7FJREFUWAnNV1lIlFEU/u4/45gLY3symWkZhGNaRBst6kMEFS2QD1FQEBVFEUUPhdBDEdJmD+09FdGTYRAktMCUT4YttvqQlIaZSxEamk4zczvnOv8w0/z/LI5WB/Teueec7zv3nvPf//wCMYrzbZmtt02UeoE1kDIfEA5A0h+LaKN5G4R4ZwHupDmk662zyj2oi/xfRFYDOa6yTOnGEQmxSULao9mzXkD0CMibwoajzaVV7ZF8TAPIe783eeBjRzk5H6Adp0UCMdUJ0Uu6yuTcScebZpwbMLIzDIB37f0lbhPxQiOnuNeEqLMkyfVGpxEWQO7DjYUer+cukWTFTRTZoTVJw8oPy6teB5uFBKB27kb9CJDrnK0WG+YFn4Smazjn6tiHf+c6BY9ZzMFc+mIgAFVww5VzHd1oJA5/cSutSoG/6JqGXO1GRJHW6OmgoszjVKgT4Od8uMmTNZt5CPRYK06y0PiG40vG3Dp+zbrMJXAtPou8tMmmzszJ3Bpfr7HecKZoQYqlYwtxpmA3slImoHr+MdMgmJO5NXW3BwEkMp1ln4arsw8iSbMqmFc9H9DcZ34TM7dGuacXS+IyNWUSrs85jDTrKAX2msh3NJyGRxKNmRA3FSG/1RKTcTY7bswtx/jkDAXU0teBLc8r0OftjwIsHBSA/ko1t102rghnC/bAqLJTLaNwjXaek5qpAL4OdGPzs+P46u42BwxopGMwWYGF8El2ykScL9yH0UnpmJmeje0Np9Da36UMrcKCK0UHUJQxXf3u9fRj64sKtPw0z3swg6BK5BRQM2EuC8bkw25NVQZOew5qFp0AVzrLKecuFI+frea/fB7sfHkGXHixihTii5hyv8wFiZJITpwC/RTYzit9qP/eiIVjncpNSon9by6g+kttJJhwncAjjduocE3oSu23l1hddwiNP1qUwiK0ADkvVLy/GT85OxK3xj0cz6PJp5+dWPukHA86n4aYurpe4HJzTBAhfvyDuTVuILmHC9MaLPT73NjWcBK3Pj+i60OqS2YLFd1QhDkHucl76r2yiz5gVzxAGxzFqGmvQ5/PsNWLCkXVf6llRdVuGikV1L1SPriBjFlutT0eMjlzKU5iUwH4W6TKmNkTN6zU2zIVAONx60yR1SWOHQWBOBSX3+z/aUo5ID4Wq8W6iqat/gCHc1BtuX70OnDICeiLf/PDJFADOjmPHCXlqYRq4li8T0cwjvIlDMb6c+e6neEJ6Eoe+TT+ycdpcBA8H6nP898PW2+tnIPs1AAAAABJRU5ErkJggg==";
            bd_nd_B937DB990D1548698380D65CF906E308.iconYELLOW = "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAABGdBTUEAALGPC/xhBQAAAsZJREFUWAnFVz1oFEEUfm/M7W5OsDAI5kiRIlgopBPSGGIbIWCTwpje2la0OLG1VGvlLNIIB9omWAXEJiGpUqRYLkJICiGX3dPc871Zd93N7c7uxg07cLtz7+/7dmbezBuEgo3W7li+d3wfEJeA6DYAtgCIf9Kwx/0e63ZZ17Wd6+u4vDMIdOYnmtUcdm36pu8NXnBvhQiu5dmLHhF+8rNjO1Ybl/d/mHwyCdCXGds76j9DoqcMfNUUJEvHRE4I8bUz0XyFi3t+ml0qAflq73Twib96Ls2pvAw3nXHrYdpojBDwP07NDn8PP/NcTpUHMnggukqpRfuxux23ShDQX+4NvlUOHiIyCcex7sZHQoU6Pecy7FV/eQggb44tUytYoXgs7MiCKzPnODEL2JzU7tQ/ADraCkPlvGkuwALOLM4VeQSp5u+VWe2N+XdwZXpJ3OFsvwu/vj7R/SIPyQ7bsWdkKvQUSJ6XAS8CYrIRrGBvAVCyw/EYrJgcLkfHGxtjK9lemVGhHa5KIoIp2Erv7VVGLhOLzxXFqcEHS02NsXkRyqlWV8MWEwiP1DpIkBCosREQ74S6mLhVlsbw8HvkEu9HwiIdxAP03k+uc0osFLGv2oZ3xA1Jw92qAxeOx9iSht3CDglDPkZQkkiWUeJUT1gZ/zC20gWkruGMpiPKxvxbcFZd/WvcezOizxNI3SjYKqhesZPnYNTTmVGdrsSOYOs01NUrH5HphkWkVMQosgmOY6stgmjyTj+02jCk55FVTidRkJz0gI4TpZ7ZW+HL8dXev4JErHVJdtjf4F5FlXAWB66QbzQXwjI9GgFNQsrxuopSIaBLpDH1gPcGN4v/heV/y/J4RSyx9CKMB7UfuVtSOjOdzbj8//o87Bzz/J1AYo4QEKGwlHkCXiyyYkV2kaZ9OYae84w7YmINpIHUdjk9T+ayrud/ADyVIY8l5unaAAAAAElFTkSuQmCC";
            bd_nd_B937DB990D1548698380D65CF906E308.iconRED = "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAABGdBTUEAALGPC/xhBQAAAslJREFUWAnFV89rE0EUnjdN0lZByMX016HQ4o9GvQke67EKgmf/Bw+9FnuoeNOi/g89C0LpsT0WPCjWjYhVcohJ40UQtG2S7vN9s2zc3WzTmXZLBnZ39s1773sz8+btt6QsG5fLhYY6vMu+/4CZ5oh4QimSC43rIquLrEJavx1Xw5vkea1grP+d+g8r9bNcHuv4+8sC8IgVXzpJH+Ok6LcEs5bToyuXPW+vn82xAfDC7HCjyksCusisLvZzctwYkfojwayOT9Mz2tg9TNNLDQCzbvkHbxTznTQjZxnRdkGPPExbjZ4Amjeu3mp3Ouuyr1POQH0NqJbL872xne87UbVYAGbmRwfvsgcPIalWGBq5HV0JHQ5hz82yZz7zEAFPngIGsEJpLuwg4Vz2PF++qYZKJWN+1Gyqthdb2dBt71PyqlFVSzKwjEGzBVj6tr+/65LtxdXX6sLCffhQfzfW1a/Fx6Zvc8PpyOvRWWyF2YLgnJ/uqNkAJnUwUWBCrlHhUGSSSuf9bgqbYGtTXi0rXJZBoaoCW6O2Z+nYxRewtSzFnItRlrrA1sFXLUu39r6ALacg/KTaG2anSQhggE0yUSoh1yWEK65htD6875pE+12hTYe4QbVrM5sSxLyNfvY6tIUkrGTv2M4jsDU4nJ16QksKutKSQrjQP0UDtjYEUjicq33xxSs16X01V/H5S1dzwxuBrcFeZSnWnD1EDXw/+mbVByawzTEEe8Un0soyTckxAGABE666m1e/PrPiMz9J858mixGSvYZqV7w0tVSZZP7Tic/f/hMSaIEm/ajylgsrSvV+klAY8uQ0zYc0vbsCsBsoKUUAoEj5XE54FtXwnm0LaHmUEcO/ScIoUOnTl4+gznK2t6PyM/XxYyI+k/8E8NkTAISIEvuEZDnL6YAtfMBXcubAQYvlQCCK35EXA/k5jYchp+Scfs//ATBhNdoIKVgAAAAAAElFTkSuQmCC";
        } else {
            bd_nd_B937DB990D1548698380D65CF906E308.iconGREEN = bd_nd_B937DB990D1548698380D65CF906E308.ICON_GREEN;
            bd_nd_B937DB990D1548698380D65CF906E308.iconYELLOW = bd_nd_B937DB990D1548698380D65CF906E308.ICON_WARN;
            bd_nd_B937DB990D1548698380D65CF906E308.iconRED = bd_nd_B937DB990D1548698380D65CF906E308.ICON_RED; }

        if (document.body.currentStyle) {
            bd_nd_B937DB990D1548698380D65CF906E308.dir = document.body.currentStyle["direction"]; }
        else if (window.getComputedStyle) {
            bd_nd_B937DB990D1548698380D65CF906E308.dir = document.defaultView.getComputedStyle(document.body, null).getPropertyValue("direction"); }

        if (window.XMLHttpRequest) {
            bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp = new XMLHttpRequest(); }
        else if (window.ActiveXObject) {
            bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp = new ActiveXObject("Microsoft.XMLHTTP"); }
    },

    getIconIdx: function (iconx) {
        var idx = parseInt(iconx.id.substr(bd_nd_B937DB990D1548698380D65CF906E308.ICON_PREFIX.length));
        if (isNaN(idx)
            || (idx < 0)
            || (idx >= bd_nd_B937DB990D1548698380D65CF906E308.links.length)) {
            return -1; }
        return idx;
    },

    getPos: function (elem) {
        var pa = { x: 0, y: 0 },
			doc = elem && elem.ownerDocument;

        if (!doc) return pa;

        var docElem = doc.documentElement || document.body.parentNode || doc.body;
        var win = doc.defaultView || doc.parentWindow;

        var bbox = { top: 0, left: 0 };

        if (typeof elem.getBoundingClientRect !== "undefined") {
            bbox = elem.getBoundingClientRect(); }

        var xscroll = win.pageXOffset || docElem.scrollLeft;
        var yscroll = win.pageYOffset || docElem.scrollTop;

        pa.y = bbox.top + yscroll - docElem.clientTop;
        pa.x = bbox.left + xscroll - docElem.clientLeft;

        return pa;
    },

    createToolTip: function (iconx) {
        //console.log('bd_nd_B937DB990D1548698380D65CF906E308...createToolTip');

        var tooltip = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP"));
        if (tooltip != null) {
            bd_nd_B937DB990D1548698380D65CF906E308.console_log = tooltip;
            return; }

        if (bd_nd_B937DB990D1548698380D65CF906E308.tooltipGREEN == null) {
            bd_nd_B937DB990D1548698380D65CF906E308.tooltipGREEN = new String();
            if (bd_nd_B937DB990D1548698380D65CF906E308.canEmbed()) {
                bd_nd_B937DB990D1548698380D65CF906E308.tooltipGREEN = "data:image/png;base64,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";
            } else {
                bd_nd_B937DB990D1548698380D65CF906E308.tooltipGREEN = bd_nd_B937DB990D1548698380D65CF906E308.TOOLTIP_GREEN;
            }
        }
        if (bd_nd_B937DB990D1548698380D65CF906E308.tooltipYELLOW == null) {
            bd_nd_B937DB990D1548698380D65CF906E308.tooltipYELLOW = new String();
            if (bd_nd_B937DB990D1548698380D65CF906E308.canEmbed()) {
                bd_nd_B937DB990D1548698380D65CF906E308.tooltipYELLOW = "data:image/png;base64,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";
            } else {
                bd_nd_B937DB990D1548698380D65CF906E308.tooltipYELLOW = bd_nd_B937DB990D1548698380D65CF906E308.TOOLTIP_YELLOW;
            }
        }
        if (bd_nd_B937DB990D1548698380D65CF906E308.tooltipRED == null) {
            bd_nd_B937DB990D1548698380D65CF906E308.tooltipRED = new String();
            if (bd_nd_B937DB990D1548698380D65CF906E308.canEmbed()) {
                bd_nd_B937DB990D1548698380D65CF906E308.tooltipRED = "data:image/png;base64,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";
            } else {
                bd_nd_B937DB990D1548698380D65CF906E308.tooltipRED = bd_nd_B937DB990D1548698380D65CF906E308.TOOLTIP_RED;
            }
        }

        var body = ((iconx != null) ? iconx.ownerDocument.getElementsByTagName("body")[0] : document.getElementsByTagName("body")[0]);

        tooltip = ((iconx != null) ? iconx.ownerDocument.createElement("div") : document.createElement("div"));
        tooltip.id = "bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP";
        tooltip.style.display = "none";
        tooltip.style.zIndex = 1000;
        tooltip.style.position = "absolute";
        tooltip.style.width = "416px";
        tooltip.style.height = "108px";
        tooltip.style.left = "0px";
        tooltip.style.top = "0px";
    		tooltip.style.backgroundColor = "#ffffff";
    		tooltip.style.border = "1px solid #eeeeee";
    		tooltip.style.fontFamily = "Segoe UI, Arial, sans-serif";

        var tooltipImg = ((iconx != null) ? iconx.ownerDocument.createElement("img") : document.createElement("img"));
        tooltipImg.id = "bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_IMG";
        tooltipImg.style.border = "none 0pt #000000";
        tooltipImg.style.backgroundColor = "#f2f2f2";
        tooltipImg.style.width = "96px";
        tooltipImg.style.height = "109px";
		tooltipImg.style.position = "absolute";
		tooltipImg.style.top = "0px";
        tooltipImg.style.left = "0px";

        var tooltipHeader = ((iconx != null) ? iconx.ownerDocument.createElement("div") : document.createElement("div"));
        tooltipHeader.id = "bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_HEADER";
        tooltipHeader.style.position = "absolute";
        tooltipHeader.style.bottom = "12px";
        tooltipHeader.style.left = "112px";
        tooltipHeader.style.width = "100%";
        tooltipHeader.style.height = "20px";
        tooltipHeader.style.visibility = "hidden";
        tooltipHeader.innerHTML = bd_nd_B937DB990D1548698380D65CF906E308.title;
        tooltipHeader.style.color = "#000000";
        tooltipHeader.style.fontSize = "13px";
        tooltipHeader.style.textAlign = "left";
        tooltipHeader.style.fontFamily = "Segoe UI Semibold, Arial, sans-serif";

        var tooltipTitle = ((iconx != null) ? iconx.ownerDocument.createElement("div") : document.createElement("div"));
        tooltipTitle.id = "bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_TITLE";
        tooltipTitle.style.position = "absolute";
        tooltipTitle.style.top = "12px";
        tooltipTitle.style.left = "112px";
        tooltipTitle.style.width = "100%";
        tooltipTitle.style.visibility = "hidden";
        tooltipTitle.innerHTML = "";
        tooltipTitle.style.color = "#000000";
        tooltipTitle.style.fontSize = "15px";
        tooltipTitle.style.fontWeight = "bold";
        tooltipTitle.style.textAlign = "left";

        var tooltipContent = ((iconx != null) ? iconx.ownerDocument.createElement("div") : document.createElement("div"));
        tooltipContent.id = "bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_CONTENT";
        tooltipContent.style.position = "absolute";
        tooltipContent.style.top = "35px";
        tooltipContent.style.left = "112px";
        tooltipContent.style.width = "288px";

        tooltipContent.style.visibility = "hidden";
        tooltipContent.innerHTML = "";
        tooltipContent.style.color = "#404040";
        tooltipContent.style.fontSize = "13px";
        tooltipContent.style.textAlign = "left";

        tooltip.appendChild(tooltipImg);
        tooltip.appendChild(tooltipHeader);
        tooltip.appendChild(tooltipTitle);
        tooltip.appendChild(tooltipContent);
        body.appendChild(tooltip);
        tooltipImg.src = ""
    },

    destroyToolTip: function (iconx) {
        //console.log('bd_nd_B937DB990D1548698380D65CF906E308...destroyToolTip');
        var tooltipHeader = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_HEADER") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_HEADER"));
        if (tooltipHeader != null) {
            tooltipHeader.parentNode.removeChild(tooltipHeader); }
        var tooltipTitle = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_TITLE") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_TITLE"));
        if (tooltipTitle != null) {
            tooltipTitle.parentNode.removeChild(tooltipTitle); }
        var tooltipContent = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_CONTENT") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_CONTENT"));
        if (tooltipContent != null) {
            tooltipContent.parentNode.removeChild(tooltipContent); }
        var tooltipImg = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_IMG") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_IMG"));
        if (tooltipImg != null) {
            tooltipImg.parentNode.removeChild(tooltipImg); }
        var tooltip = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP"));
        if (tooltip != null) {
            tooltip.parentNode.removeChild(tooltip); }
    },

    showToolTip: function (iconx) {
        //console.log('bd_nd_B937DB990D1548698380D65CF906E308...showToolTip');
        var n = bd_nd_B937DB990D1548698380D65CF906E308.getIconIdx(iconx);
        if ((n < 0)
            || (n >= bd_nd_B937DB990D1548698380D65CF906E308.links.length)) {
            //console.log('bd_nd_B937DB990D1548698380D65CF906E308...showToolTip...!NDX: ' + n);
            bd_nd_B937DB990D1548698380D65CF906E308.destroyToolTip(iconx);
            return; }
        if ((bd_nd_B937DB990D1548698380D65CF906E308.links[n][0] != bd_nd_B937DB990D1548698380D65CF906E308.STATUS_READY)
            || (bd_nd_B937DB990D1548698380D65CF906E308.links[n][1] == 0)) {
            bd_nd_B937DB990D1548698380D65CF906E308.destroyToolTip(iconx);
            //console.log('bd_nd_B937DB990D1548698380D65CF906E308...showToolTip...!STATUS_READY');
            return; }

        var tooltip = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP"));
        var tooltipImg = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_IMG") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_IMG"));
        var tooltipHeader = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_HEADER") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_HEADER"));
        var tooltipTitle = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_TITLE") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_TITLE"));
        var tooltipContent = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_CONTENT") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_CONTENT"));
        if ((tooltip == null) || (tooltipImg == null) || (tooltipHeader == null) || (tooltipTitle == null) || (tooltipContent == null)) {
            bd_nd_B937DB990D1548698380D65CF906E308.destroyToolTip(iconx);
            bd_nd_B937DB990D1548698380D65CF906E308.createToolTip(iconx);
            tooltip = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP"));
            tooltipImg = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_IMG") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_IMG"));
            tooltipHeader = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_HEADER") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_HEADER"));
            tooltipTitle = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_TITLE") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_TITLE"));
            tooltipContent = ((iconx != null) ? iconx.ownerDocument.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_CONTENT") : document.getElementById("bd_nd_B937DB990D1548698380D65CF906E308_TOOLTIP_CONTENT")); }
        if ((tooltip == null) || (tooltipImg == null) || (tooltipHeader == null) || (tooltipTitle == null) || (tooltipContent == null)) {
            //console.log('bd_nd_B937DB990D1548698380D65CF906E308...showToolTip...!tooltip');
            bd_nd_B937DB990D1548698380D65CF906E308.destroyToolTip(iconx);
            return; }

        if (bd_nd_B937DB990D1548698380D65CF906E308.links[n][1] == bd_nd_B937DB990D1548698380D65CF906E308.STATUS_GREEN) {
            tooltipImg.src = bd_nd_B937DB990D1548698380D65CF906E308.tooltipGREEN;
            tooltipTitle.innerHTML = bd_nd_B937DB990D1548698380D65CF906E308.green_title;
            tooltipContent.innerHTML = bd_nd_B937DB990D1548698380D65CF906E308.green_content; }
        else if (bd_nd_B937DB990D1548698380D65CF906E308.links[n][1] == bd_nd_B937DB990D1548698380D65CF906E308.STATUS_YELLOW) {
                tooltipImg.src = bd_nd_B937DB990D1548698380D65CF906E308.tooltipYELLOW;
                tooltipTitle.innerHTML = bd_nd_B937DB990D1548698380D65CF906E308.yellow_title;
                tooltipContent.innerHTML = bd_nd_B937DB990D1548698380D65CF906E308.yellow_content; }
        else if (bd_nd_B937DB990D1548698380D65CF906E308.links[n][1] == bd_nd_B937DB990D1548698380D65CF906E308.STATUS_RED) {
            tooltipImg.src = bd_nd_B937DB990D1548698380D65CF906E308.tooltipRED;
            tooltipTitle.innerHTML = bd_nd_B937DB990D1548698380D65CF906E308.red_title;
            tooltipContent.innerHTML = bd_nd_B937DB990D1548698380D65CF906E308.red_content; }
        else {
            bd_nd_B937DB990D1548698380D65CF906E308.destroyToolTip(iconx);
            //console.log('bd_nd_B937DB990D1548698380D65CF906E308...showToolTip...!status');
            return; }

        var p = bd_nd_B937DB990D1548698380D65CF906E308.getPos(iconx);
        var x = p.x;
        var y = p.y + 28;
        tooltip.style.left = x + "px";
        tooltip.style.top = y + "px";
        tooltip.style.display = "block";
        tooltipHeader.style.visibility = "visible";
        tooltipTitle.style.visibility = "visible";
        tooltipContent.style.visibility = "visible";
    },

    hideToolTip: function (iconx) {
        //console.log('bd_nd_B937DB990D1548698380D65CF906E308...hideToolTip');
        bd_nd_B937DB990D1548698380D65CF906E308.destroyToolTip(iconx);
    },

    onClickLink: function (e) {
        //console.log('bd_nd_B937DB990D1548698380D65CF906E308...onClickLink');
        //try {
        var obj;
        if (typeof event != "undefined") {
            obj = event.srcElement ? event.srcElement : event.target; }
        else {
            obj = this; }
        if (typeof e != "undefined") {
            e.preventDefault();
            e.stopPropagation(); }
        else if (typeof window.event != "undefined") {
            window.event.returnValue = false;
            window.event.cancelBubble = true; }

        if (obj == null) {
            return; }
        bd_nd_B937DB990D1548698380D65CF906E308.destroyToolTip(obj);
        var anchor = obj.parentNode;
        if (anchor == null) {
            return; }
        // window.open(anchor.href, "_blank"); // 4342
    },

    onMouseOver: function () {
        //console.log('bd_nd_B937DB990D1548698380D65CF906E308...onMouseOver');
        var obj;
        if (typeof event != "undefined") {
            obj = event.srcElement ? event.srcElement : event.target; }
        else {
            obj = this; }
        if (obj == null) {
            return; }
        bd_nd_B937DB990D1548698380D65CF906E308.showToolTip(obj);
    },

    onMouseOut: function () {
        //console.log('bd_nd_B937DB990D1548698380D65CF906E308...onMouseOut');
        var obj;
        if (typeof event != "undefined") {
            obj = event.srcElement ? event.srcElement : event.target; }
        else {
            obj = this; }
        bd_nd_B937DB990D1548698380D65CF906E308.hideToolTip(obj);
    },

    createIconx: function (ndx) {
        if ((ndx < 0)
            || (ndx >= bd_nd_B937DB990D1548698380D65CF906E308.links.length)
            || (bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][0] != bd_nd_B937DB990D1548698380D65CF906E308.STATUS_READY)
            || (bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][1] == 0)
            || (bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][3] == null)) {
            return; }
        if (bd_nd_B937DB990D1548698380D65CF906E308.isKnownLink(bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][3])) {
            //console.log('createIconx.known: ' + ndx);
            return; }

        var anchor_id = bd_nd_B937DB990D1548698380D65CF906E308.ANCHOR_PREFIX + ndx;
        var anchor = bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][3].ownerDocument.getElementById(anchor_id);
        if (anchor == null) {
            var kblink = bd_nd_B937DB990D1548698380D65CF906E308.fraud_link;
            var linkparser = bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][3].ownerDocument.createElement('a');
            linkparser.href = kblink;
            if (linkparser.host == null) {
                kblink = "https://trafficlight.bitdefender.com/info?url="; }

            anchor = bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][3].ownerDocument.createElement("span");
            anchor.id = anchor_id;
            //anchor.href = kblink.replace("{URL}", escape(bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][2])); // 4342
            anchor.style.display = "none";
            anchor.style.visibility = "hidden";

            bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][3].parentNode.insertBefore(anchor, bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][3]);
            bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][4] = anchor;

            bd_nd_B937DB990D1548698380D65CF906E308.links.push([bd_nd_B937DB990D1548698380D65CF906E308.STATUS_SKIPPED, 0, null, anchor, null, -1, 0]);
        }

        var icon_id = bd_nd_B937DB990D1548698380D65CF906E308.ICON_PREFIX + ndx;
        var icon = bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][3].ownerDocument.getElementById(icon_id);
        if (icon == null) {
            icon = bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][3].ownerDocument.createElement("img");
			var icon_class = bd_nd_B937DB990D1548698380D65CF906E308.ICON_PREFIX;
            icon.id = icon_id;
            icon.style.border = "0px";
            icon.style.cursor = "pointer";
            icon.style.display = "inline";
            icon.style.marginRight = "3px";
            icon.style.height = "16px";
            icon.style.width = "16px";

            if (bd_nd_B937DB990D1548698380D65CF906E308.isGoogle && bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][3].parentNode.tagName.toLowerCase() !== "h3") {
                anchor.style.marginLeft = "-20px";
                anchor.style.verticalAlign = "top";
                icon.style.verticalAlign ="middle";
            }

            if (bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][1] == bd_nd_B937DB990D1548698380D65CF906E308.STATUS_GREEN) {
                icon.src = bd_nd_B937DB990D1548698380D65CF906E308.iconGREEN; 
				icon.className = icon_class + "green"; }
            else if (bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][1] == bd_nd_B937DB990D1548698380D65CF906E308.STATUS_YELLOW) {
                icon.src = bd_nd_B937DB990D1548698380D65CF906E308.iconYELLOW; 
				icon.className = icon_class + "yellow"; }
            else if (bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][1] == bd_nd_B937DB990D1548698380D65CF906E308.STATUS_RED) {
                icon.src = bd_nd_B937DB990D1548698380D65CF906E308.iconRED; 
				icon.className = icon_class + "red"; }
            anchor.appendChild(icon);
        }
        anchor.style.display = bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][3].style.display;
        anchor.style.visibility = bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][3].style.visibility;
        if (window.addEventListener) {
            icon.addEventListener("mouseover", bd_nd_B937DB990D1548698380D65CF906E308.onMouseOver, false);
            icon.addEventListener("mouseout", bd_nd_B937DB990D1548698380D65CF906E308.onMouseOut, false);
            icon.addEventListener("click", bd_nd_B937DB990D1548698380D65CF906E308.onClickLink, false);
        } else if (window.attachEvent) {
            icon.attachEvent("onmouseover", bd_nd_B937DB990D1548698380D65CF906E308.onMouseOver);
            icon.attachEvent("onmouseout", bd_nd_B937DB990D1548698380D65CF906E308.onMouseOut);
            icon.attachEvent("onclick", bd_nd_B937DB990D1548698380D65CF906E308.onClickLink); }
    },

    isKnownLink: function (link) {
        var linkId = link.id;
        if ((linkId != "undefined")
            && (linkId != null)) {
            linkId = linkId.substr(0, bd_nd_B937DB990D1548698380D65CF906E308.ANCHOR_PREFIX.length);
            if (linkId == bd_nd_B937DB990D1548698380D65CF906E308.ANCHOR_PREFIX) {
                return true; } }
        var anchor = link.previousSibling;
        if ((anchor == "undefined") || (anchor == null)) {
            return false; }
        linkId = anchor.id;
        if ((linkId != "undefined")
            && (linkId != null)) {
            linkId = linkId.substr(0, bd_nd_B937DB990D1548698380D65CF906E308.ANCHOR_PREFIX.length);
            if (linkId == bd_nd_B937DB990D1548698380D65CF906E308.ANCHOR_PREFIX) {
                return true; }
        }
        return false;
    },

	addLink: function (link, url) {
	    if ((url == null) || (url == "undefined") || (url == "")) {
	        url = link.href; }
	    if ((url == null) || (url == "undefined") || (url == "")) {
	        return; }
	    if (bd_nd_B937DB990D1548698380D65CF906E308.isKnownLink(link)) {
	        //console.log('addLink.known: ' + unescape(url));
	        return; }
	    if (null == bd_nd_B937DB990D1548698380D65CF906E308.links) {
	        bd_nd_B937DB990D1548698380D65CF906E308.links = []; }
	    var alias = [bd_nd_B937DB990D1548698380D65CF906E308.STATUS_ADDED,0,-1];
	    for (var i = 0; i < bd_nd_B937DB990D1548698380D65CF906E308.links.length; i++) {
	        if (link == bd_nd_B937DB990D1548698380D65CF906E308.links[i][3]) {
	            return; }
	        if (url == bd_nd_B937DB990D1548698380D65CF906E308.links[i][2]) {
	            alias = [bd_nd_B937DB990D1548698380D65CF906E308.STATUS_ALIAS, bd_nd_B937DB990D1548698380D65CF906E308.links[i][1], i];
	            break; } }
	    bd_nd_B937DB990D1548698380D65CF906E308.links.push([alias[0], alias[1], url, link, null, alias[2], 0]);
	},

	processLinks: function () {
	    if (bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp == null) {
	        return; }
	    if (null == bd_nd_B937DB990D1548698380D65CF906E308.links) {
	        return; }
	    var links = [];
	    for (var i = 0; i < bd_nd_B937DB990D1548698380D65CF906E308.links.length; i++) {
	        if (bd_nd_B937DB990D1548698380D65CF906E308.links[i][0] == bd_nd_B937DB990D1548698380D65CF906E308.STATUS_ADDED) {
	            links.push([bd_nd_B937DB990D1548698380D65CF906E308.links[i][2], i]);
	        } else if (bd_nd_B937DB990D1548698380D65CF906E308.links[i][0] == bd_nd_B937DB990D1548698380D65CF906E308.STATUS_READY) {
	            var anchor_id = bd_nd_B937DB990D1548698380D65CF906E308.ANCHOR_PREFIX + i;
	            var anchor = bd_nd_B937DB990D1548698380D65CF906E308.links[i][3].ownerDocument.getElementById(anchor_id);
	            if (anchor != null) {
	                anchor.style.display = bd_nd_B937DB990D1548698380D65CF906E308.links[i][3].style.display;
	                anchor.style.visibility = bd_nd_B937DB990D1548698380D65CF906E308.links[i][3].style.visibility;
                }
	        } else if (bd_nd_B937DB990D1548698380D65CF906E308.links[i][0] == bd_nd_B937DB990D1548698380D65CF906E308.STATUS_ALIAS) {
	            var alias = bd_nd_B937DB990D1548698380D65CF906E308.links[i][5];
	            if (bd_nd_B937DB990D1548698380D65CF906E308.links[alias][0] == bd_nd_B937DB990D1548698380D65CF906E308.STATUS_READY) {
	                bd_nd_B937DB990D1548698380D65CF906E308.links[i][0] = bd_nd_B937DB990D1548698380D65CF906E308.links[alias][0];
	                bd_nd_B937DB990D1548698380D65CF906E308.links[i][1] = bd_nd_B937DB990D1548698380D65CF906E308.links[alias][1];
	                bd_nd_B937DB990D1548698380D65CF906E308.createIconx(i);
	            }
	        }
        }
	    if (links.length == 0) {
	        return; }
	    for (var i = 0; i < links.length; i++) {
	        //console.log('ls.processLinks[' + i + ']=[' + links[i][1] + '] ' + links[i][0]); 
		}

	    bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp.onreadystatechange = function () {
	        if (bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp.readyState == 4) {
	            //console.log('(bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp = (' + bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp.readyState + ', ' + bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp.status + ')');
	            if (bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp.status == 200) {
	                bd_nd_B937DB990D1548698380D65CF906E308.handleResponse(bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp.responseXML);
	            }
            }
	    }
	    var sid = Math.random();
	    bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp.open("GET", sid, true);
	    bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp.setRequestHeader("BDNDSS_B67EA559F21B487F861FDA8A44F01C50", "NDSECK_6cabeba2cb54e038ed83ce3ac0c42332");
	    bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp.setRequestHeader("BDNDCA_BBACF84D61A04F9AA66019A14B035478", "NDCA_6cabeba2cb54e038ed83ce3ac0c42332");
	    bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp.setRequestHeader(bd_nd_B937DB990D1548698380D65CF906E308.HEADER_NAME, "ls.scan");
	    for (var i = 0; i < links.length; i++) {
	        bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp.setRequestHeader(bd_nd_B937DB990D1548698380D65CF906E308.HEADER_NAME + i, links[i][1] + ',' + links[i][0]); }
	    bd_nd_B937DB990D1548698380D65CF906E308.xmlhttp.send(null);
	},

	handleResponse: function (xml) {
	    try {
	        var roottag = xml.getElementsByTagName("netdefender")[0];
	    } catch (err) {
	        //console.log('handleResponse' + err);
	        return; }
	    //console.log('handleResponse');
	    if (roottag == null) {
	        return; }
	    var responses = [];
	    for (var i = 0; i < roottag.childNodes.length; i++) {
	        var ok = false;
	        try {
	            var urlTag = roottag.childNodes[i];
	            if (urlTag.tagName != "url") {
	                continue; }
	            var index = parseInt(urlTag.getAttribute("index"));
	            var result = parseInt(urlTag.getAttribute("result"));
	            if (isNaN(index)
                    || isNaN(result)) {
	                continue; }
	            responses.push([index, result]);
	            //console.log('ls.handleResponse[' + index + ']=' + result);
            } catch (error) {
                console.error(error);
            }
	    }
	    for (var i = 0; i < responses.length; i++) {
	        var ndx = responses[i][0];
	        if ((ndx < 0)
                || (ndx >= bd_nd_B937DB990D1548698380D65CF906E308.links.length)) {
	            continue; }
	        var scanResult = 0;
	        if (responses[i][1] == 0) {
	            scanResult = bd_nd_B937DB990D1548698380D65CF906E308.STATUS_GREEN; }
	        else if (responses[i][1] == 1) {
	            scanResult = bd_nd_B937DB990D1548698380D65CF906E308.STATUS_YELLOW; }
	        else if (responses[i][1] == 2) {
	            scanResult = bd_nd_B937DB990D1548698380D65CF906E308.STATUS_RED; }
	        else {
	            continue; }
	        bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][0] = bd_nd_B937DB990D1548698380D65CF906E308.STATUS_READY;
	        bd_nd_B937DB990D1548698380D65CF906E308.links[ndx][1] = scanResult;
	        bd_nd_B937DB990D1548698380D65CF906E308.createIconx(ndx);

	        for (var j = 0; j < bd_nd_B937DB990D1548698380D65CF906E308.links.length; j++) {
	            if (bd_nd_B937DB990D1548698380D65CF906E308.links[j][0] != bd_nd_B937DB990D1548698380D65CF906E308.STATUS_ALIAS) {
	                continue; }
	            if (bd_nd_B937DB990D1548698380D65CF906E308.links[j][5] == ndx) {
	                bd_nd_B937DB990D1548698380D65CF906E308.links[j][0] = bd_nd_B937DB990D1548698380D65CF906E308.STATUS_READY;
	                bd_nd_B937DB990D1548698380D65CF906E308.links[j][1] = scanResult;
	                bd_nd_B937DB990D1548698380D65CF906E308.createIconx(j);
	            }
	        }

        }
	},

	start: function () {
	    bd_nd_B937DB990D1548698380D65CF906E308.init();
	}
};
var bd_nd_facebook_B937DB990D1548698380D65CF906E308 = 
{

	TIMEOUT					: 3000,
	ANCHOR_HREF				: ".facebook.com/l.php?u=",
	ANCHOR_REGEX_HREF		: "\\.facebook\\.com/[al]\\.php\\?u=",
	ANCHOR_REGEX_INTERNAL	: "^https?://([^.]*?\\.)*facebook\\.com",
	ANCHOR_REGEX_ABSOLUTE: "^(?:[a-z]+:)?//",
	ANCHOR_REGEX_FBCLID     : new RegExp(/(^http(?:s)?:\/\/.*)([?&]fbclid=[^&]+)/i),
	ANCHOR_CLASS_1			: "shareMediaLink",
	ANCHOR_CLASS_2			: "tickerStoryAllowClick",
	ANCHOR_CLASS_3			: "external",
	ANCHOR_CLASS_4			: "uiHeaderActions",
	ANCHOR_CLASS_5			: "shareLink",
	IMG_CLASS_1				: "fbStoryAttachmentImage",
	IMG_CLASS_2				: "music_artwork",
	IMG_CLASS_3				: "music_artwork_grid",
	lastQueue				: 0,
	lastScan				: 0,
	timeoutID				: -1,
	timeoutID				: -1,
	
	queueUpdateLinks : function () {
		var currTime = Date.now();
		if ((currTime - this.lastScan) > this.TIMEOUT) {
			this.updateLinks();
			this.lastScan = Date.now();
			clearTimeout(this.timeoutID);
			this.timeoutID = setTimeout(this.updateLinks, this.TIMEOUT);
			return;
		} else {
			clearTimeout(this.timeoutID);
			this.timeoutID = setTimeout(this.updateLinks, (this.lastScan + this.TIMEOUT) - currTime);
		}		
	},
	
	repeatUpdateLinks : function () {
		this.updateLinks();
		setTimeout("bd_nd_facebook_B937DB990D1548698380D65CF906E308.repeatUpdateLinks()", this.TIMEOUT);
	},
	
	parseURL : function(url, what)
	{
		var pos = url.indexOf(what);
		if (pos == 0)
		{
			return url.substr(pos + what.length);
		}
		return url;
	},

	updateLinks : function()
	{
	    console.log("facebook.updateLinks");
		var anchors = document.getElementsByTagName("a"); 
		if (null != anchors)
		{
			var anchorRegex = new RegExp(bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_REGEX_HREF);
			var internalRegex = new RegExp(bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_REGEX_INTERNAL);
			var absoluteTest = new RegExp(bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_REGEX_ABSOLUTE, 'i');
		
			for (var i = 0; i < anchors.length; i++)
			{
				var targetAnchor = anchors[i];
				var targetHref = targetAnchor.href;
				
				if (!absoluteTest.test(targetHref)) {
					targetHref = targetAnchor.baseURI + targetHref;
				}	
				
				var url = targetHref;
				
				var prefixFound = anchorRegex.exec(targetHref);
				
				if (prefixFound == null) { continue; }				
				else { 
					var urlIndex = targetHref.indexOf(prefixFound[0]);
					if (-1 != urlIndex)
					{
						url = targetHref.substr(urlIndex + prefixFound[0].length);
						var idx = url.indexOf("&");
						if (-1 != idx)
						{
							url = url.substr(0, idx);
						}
						url = unescape(url);
					}
				}
				
				if (!absoluteTest.test(url)) {
					url = targetAnchor.baseURI + url;
				}	
				
				if (url.match(internalRegex) == null)
				{
					if (targetAnchor.childNodes.length == 0) 
					{
						continue; 
					}
					
					var testElement = targetAnchor.getElementsByTagName("img")[0];
					var skipScan = false;
					
					while (testElement) {
						if (-1 < testElement.className.indexOf(bd_nd_facebook_B937DB990D1548698380D65CF906E308.IMG_CLASS_1) ||
							-1 < testElement.className.indexOf(bd_nd_facebook_B937DB990D1548698380D65CF906E308.IMG_CLASS_2) ||
							-1 < testElement.className.indexOf(bd_nd_facebook_B937DB990D1548698380D65CF906E308.IMG_CLASS_3))
						{
							skipScan = true;
							break;
						}
						
						testElement = testElement.parentElement;
						if (testElement == targetAnchor) { 
							skipScan = false; 
							break;
						}
					}
					
					if (skipScan) { continue; }
				
					if (-1 == targetAnchor.className.indexOf(bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_CLASS_1) &&
						-1 == targetAnchor.className.indexOf(bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_CLASS_2) &&
						-1 == targetAnchor.className.indexOf(bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_CLASS_3) &&
						-1 == targetAnchor.className.indexOf(bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_CLASS_4) &&
						-1 == targetAnchor.className.indexOf(bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_CLASS_5))
					{
					    var fbclid = bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_REGEX_FBCLID.exec(url);
					    if (fbclid == null) {
					        //console.log('facebook.addLink: ' + unescape(url));
					        bd_nd_B937DB990D1548698380D65CF906E308.addLink(targetAnchor, unescape(url));
					    } else {
					        //console.log('facebook.link: ' + unescape(url));
					        //console.log('facebook.addLink: ' + unescape(fbclid[1]));
					        bd_nd_B937DB990D1548698380D65CF906E308.addLink(targetAnchor, unescape(fbclid[1]));
					    }
                        
					}
				}
			}
		}
		bd_nd_B937DB990D1548698380D65CF906E308.processLinks();
	},
	
	facebookStart : function()
	{
		if (typeof(bd_nd_B937DB990D1548698380D65CF906E308) != "undefined")
		{

		    bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_HREF = ".facebook.com/l.php?u=";
		    bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_REGEX_HREF = "\\.facebook\\.com/[al]\\.php\\?u=";
		    bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_REGEX_INTERNAL = "^https?://([^.]*?\\.)*facebook\\.com";

		    var a_host = document.createElement('a');
		    a_host.href = window.location;
		    if ((a_host.host != null)
                && (a_host.host != "undefined")
                && (a_host.host == "www.messenger.com") ) {
		        bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_HREF = ".messenger.com/l.php?u=";
		        bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_REGEX_HREF = "\\.messenger\\.com/[al]\\.php\\?u=";
		        bd_nd_facebook_B937DB990D1548698380D65CF906E308.ANCHOR_REGEX_INTERNAL = "^https?://([^.]*?\\.)*messenger\\.com"; }

			bd_nd_B937DB990D1548698380D65CF906E308.start();
			
			if (window.attachEvent && !window.addEventListener) { //IE8 and lower
				bd_nd_facebook_B937DB990D1548698380D65CF906E308.repeatUpdateLinks();
				return;
			} 
			
			bd_nd_facebook_B937DB990D1548698380D65CF906E308.queueUpdateLinks();			 			
			if (window.addEventListener)
			{
				document.addEventListener("DOMNodeInserted", bd_nd_facebook_B937DB990D1548698380D65CF906E308.queueUpdateLinks.bind(bd_nd_facebook_B937DB990D1548698380D65CF906E308), true);
			}
			else
			if (window.attachEvent)
			{
				document.attachEvent("DOMNodeInserted", bd_nd_facebook_B937DB990D1548698380D65CF906E308.queueUpdateLinks.bind(bd_nd_facebook_B937DB990D1548698380D65CF906E308));
			}
		}
	}

};

	
if (bd_nd_B937DB990D1548698380D65CF906E308.isPageOK())
{
	if (window.addEventListener)
	{
		window.addEventListener("load", bd_nd_facebook_B937DB990D1548698380D65CF906E308.facebookStart.bind(bd_nd_facebook_B937DB990D1548698380D65CF906E308), false);
	}
	else
	if (window.attachEvent)
	{
		window.attachEvent("onload", bd_nd_facebook_B937DB990D1548698380D65CF906E308.facebookStart.bind(bd_nd_facebook_B937DB990D1548698380D65CF906E308));
	}
}

//]]>
</script>
<script type="text/javascript" nonce="">requireLazy(["bootstrapWebSession"],function(j){j(1648556895)})</script><div class="_li" id="u_0_3_+7"><div class="_3_s0 _1toe _3_s1 _3_s1 uiBoxGray noborder" data-testid="ax-navigation-menubar" id="u_0_4_Zu"><div class="_608m"><div class="_5aj7 _tb6"><div class="_4bl7"><span class="mrm _3bcv _50f3">Jump to</span></div><div class="_4bl9 _3bcp"><div class="_6a _608n" aria-label="Navigation assistant" aria-keyshortcuts="Alt+/" role="menubar" id="u_0_5_zW"><div class="_6a uiPopover" id="u_0_6_MM"><a role="menuitem" class="_42ft _4jy0 _55pi _2agf _4o_4 _63xb _p _4jy3 _517h _51sy" href="#" style="max-width:200px;" aria-haspopup="true" aria-expanded="false" rel="toggle" id="u_0_7_c+"><span class="_55pe">Sections of this page</span><span class="_4o_3 _3-99"><i class="img sp_AcVttjh25zD sx_755550"></i></span></a></div><div class="_6a _3bcs"></div><div class="_6a mrm uiPopover" id="u_0_8_kd"><a role="menuitem" class="_42ft _4jy0 _55pi _2agf _4o_4 _3_s2 _63xb _p _4jy3 _4jy1 selected _51sy" href="#" style="max-width:200px;" aria-haspopup="true" tabindex="-1" aria-expanded="false" rel="toggle" id="u_0_9_SB"><span class="_55pe">Accessibility help</span><span class="_4o_3 _3-99"><i class="img sp_AcVttjh25zD sx_d4ce3d"></i></span></a></div></div></div><div class="_4bl7 mlm pll _3bct"><div class="_6a _3bcy">Press <span class="_3bcz">alt</span> + <span class="_3bcz">/</span> to open this menu</div></div></div></div></div><div id="globalContainer" class="uiContextualLayerParent"><div class="fb_content clearfix " id="content" role="main"><div><div class="_8esj _95k9 _8esf _8opv _8f3m _8ilg _8icx _8op_ _95ka"><div class="_8esk"><div class="_8esl"><div class="_8ice"><img class="fb_logo _8ilh img" src="https://static.xx.fbcdn.net/rsrc.php/y8/r/dF5SId3UHWd.svg" alt="Facebook"></div><h2 class="_8eso">Facebook helps you connect and share with the people in your life.</h2></div><div class="_8esn"><div class="_8iep _8icy _9ahz _9ah-"><div class="_6luv _52jv"><form class="_9vtf" data-testid="royal_login_form" action="/login/?privacy_mutation_token=eyJ0eXBlIjowLCJjcmVhdGlvbl90aW1lIjoxNjQ4NTU2ODk1LCJjYWxsc2l0ZV9pZCI6MzgxMjI5MDc5NTc1OTQ2fQ%3D%3D" method="post" onsubmit="" id="u_0_a_M3"><input type="hidden" name="jazoest" value="2857" autocomplete="off"><input type="hidden" name="lsd" value="AVqkJE7N2-s" autocomplete="off"><div><div class="_6lux"><input type="text" class="inputtext _55r1 _6luy" name="email" id="email" data-testid="royal_email" placeholder="Email address or phone number" autofocus="1" aria-label="Email address or phone number"></div><div class="_6lux"><div class="_6luy _55r1 _1kbt" id="passContainer"><input type="password" class="inputtext _55r1 _6luy _9npi" name="pass" id="pass" data-testid="royal_pass" placeholder="Password" aria-label="Password"><div class="_9ls7 hidden_elem" id="u_0_b_XT"><a href="#" role="button"><div class="_9lsa"><div class="_9lsb" id="u_0_c_+V"></div></div></a></div></div></div></div><input type="hidden" autocomplete="off" name="login_source" value="comet_headerless_login"><input type="hidden" autocomplete="off" name="next" value=""><div class="_6ltg"><button value="1" class="_42ft _4jy0 _6lth _4jy6 _4jy1 selected _51sy" name="login" data-testid="royal_login_button" type="submit" id="u_0_d_cg">Log In</button></div><div class="_6ltj"><a href="https://www.facebook.com/recover/initiate/?privacy_mutation_token=eyJ0eXBlIjowLCJjcmVhdGlvbl90aW1lIjoxNjQ4NTU2ODk1LCJjYWxsc2l0ZV9pZCI6MzgxMjI5MDc5NTc1OTQ2fQ%3D%3D&amp;ars=facebook_login">Forgotten password?</a></div><div class="_8icz"></div><div class="_6ltg"><a role="button" class="_42ft _4jy0 _6lti _4jy6 _4jy2 selected _51sy" href="#" ajaxify="/reg/spotlight/" id="u_0_2_4S" data-testid="open-registration-form-button" rel="async">Create New Account</a></div></form></div><div id="reg_pages_msg" class="_58mk"><a href="/pages/create/?ref_type=registration_form" class="_8esh">Create a Page</a> for a celebrity, brand or business.</div></div></div></div></div></div></div><div class=""><div class="_95ke _8opy"><div id="pageFooter" data-referrer="page_footer" data-testid="page_footer"><ul class="uiList localeSelectorList _2pid _509- _4ki _6-h _6-j _6-i" data-nocookies="1"><li>English (UK)</li><li><a class="_sv4" dir="ltr" href="https://fr-fr.facebook.com/" onclick="require(&quot;IntlUtils&quot;).setCookieLocale(&quot;fr_FR&quot;, &quot;en_GB&quot;, &quot;https:\/\/fr-fr.facebook.com\/&quot;, &quot;www_list_selector&quot;, 0); return false;" title="French (France)">Français (France)</a></li><li><a class="_sv4" dir="rtl" href="https://ar-ar.facebook.com/" onclick="require(&quot;IntlUtils&quot;).setCookieLocale(&quot;ar_AR&quot;, &quot;en_GB&quot;, &quot;https:\/\/ar-ar.facebook.com\/&quot;, &quot;www_list_selector&quot;, 1); return false;" title="Arabic">العربية</a></li><li><a class="_sv4" dir="ltr" href="https://tz-ma.facebook.com/" onclick="require(&quot;IntlUtils&quot;).setCookieLocale(&quot;tz_MA&quot;, &quot;en_GB&quot;, &quot;https:\/\/tz-ma.facebook.com\/&quot;, &quot;www_list_selector&quot;, 2); return false;" title="Tamazight">ⵜⴰⵎⴰⵣⵉⵖⵜ</a></li><li><a class="_sv4" dir="ltr" href="https://es-es.facebook.com/" onclick="require(&quot;IntlUtils&quot;).setCookieLocale(&quot;es_ES&quot;, &quot;en_GB&quot;, &quot;https:\/\/es-es.facebook.com\/&quot;, &quot;www_list_selector&quot;, 3); return false;" title="Spanish (Spain)">Español (España)</a></li><li><a class="_sv4" dir="ltr" href="https://it-it.facebook.com/" onclick="require(&quot;IntlUtils&quot;).setCookieLocale(&quot;it_IT&quot;, &quot;en_GB&quot;, &quot;https:\/\/it-it.facebook.com\/&quot;, &quot;www_list_selector&quot;, 4); return false;" title="Italian">Italiano</a></li><li><a class="_sv4" dir="ltr" href="https://de-de.facebook.com/" onclick="require(&quot;IntlUtils&quot;).setCookieLocale(&quot;de_DE&quot;, &quot;en_GB&quot;, &quot;https:\/\/de-de.facebook.com\/&quot;, &quot;www_list_selector&quot;, 5); return false;" title="German">Deutsch</a></li><li><a class="_sv4" dir="ltr" href="https://pt-br.facebook.com/" onclick="require(&quot;IntlUtils&quot;).setCookieLocale(&quot;pt_BR&quot;, &quot;en_GB&quot;, &quot;https:\/\/pt-br.facebook.com\/&quot;, &quot;www_list_selector&quot;, 6); return false;" title="Portuguese (Brazil)">Português (Brasil)</a></li><li><a class="_sv4" dir="ltr" href="https://hi-in.facebook.com/" onclick="require(&quot;IntlUtils&quot;).setCookieLocale(&quot;hi_IN&quot;, &quot;en_GB&quot;, &quot;https:\/\/hi-in.facebook.com\/&quot;, &quot;www_list_selector&quot;, 7); return false;" title="Hindi">हिन्दी</a></li><li><a class="_sv4" dir="ltr" href="https://zh-cn.facebook.com/" onclick="require(&quot;IntlUtils&quot;).setCookieLocale(&quot;zh_CN&quot;, &quot;en_GB&quot;, &quot;https:\/\/zh-cn.facebook.com\/&quot;, &quot;www_list_selector&quot;, 8); return false;" title="Simplified Chinese (China)">中文(简体)</a></li><li><a class="_sv4" dir="ltr" href="https://ja-jp.facebook.com/" onclick="require(&quot;IntlUtils&quot;).setCookieLocale(&quot;ja_JP&quot;, &quot;en_GB&quot;, &quot;https:\/\/ja-jp.facebook.com\/&quot;, &quot;www_list_selector&quot;, 9); return false;" title="Japanese">日本語</a></li><li><a role="button" class="_42ft _4jy0 _517i _517h _51sy" rel="dialog" ajaxify="/settings/language/language/?uri=https%3A%2F%2Fja-jp.facebook.com%2F&amp;source=www_list_selector_more" href="#" title="Show more languages"><i class="img sp_AcVttjh25zD sx_d76731"></i></a></li></ul><div id="contentCurve"></div><div id="pageFooterChildren" role="contentinfo" aria-label="Facebook site links"><ul class="uiList pageFooterLinkList _509- _4ki _703 _6-i"><li><a href="/reg/" title="Sign up for Facebook">Sign Up</a></li><li><a href="/login/" title="Log in to Facebook">Log In</a></li><li><a href="https://messenger.com/" title="Take a look at Messenger.">Messenger</a></li><li><a href="/lite/" title="Facebook Lite for Android.">Facebook Lite</a></li><li><a href="https://www.facebook.com/watch/" title="Browse our Watch videos.">Watch</a></li><li><a href="/places/" title="Take a look at popular places on Facebook.">Places</a></li><li><a href="/games/" title="Check out Facebook games.">Games</a></li><li><a href="/marketplace/" title="Buy and sell on Facebook Marketplace.">Marketplace</a></li><li><a href="https://pay.facebook.com/" title="Learn more about Facebook Pay" target="_blank">Facebook Pay</a></li><li><a href="https://www.oculus.com/" title="Learn more about Oculus" target="_blank">Oculus</a></li><li><a href="https://portal.facebook.com/" title="Learn more about Facebook Portal" target="_blank">Portal</a></li><li><span id="bd_nd_B937DB990D1548698380D65CF906E308_anchor_0" style=""><img id="bd_nd_B937DB990D1548698380D65CF906E308_icon_0" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAABGdBTUEAALGPC/xhBQAAA7FJREFUWAnNV1lIlFEU/u4/45gLY3symWkZhGNaRBst6kMEFS2QD1FQEBVFEUUPhdBDEdJmD+09FdGTYRAktMCUT4YttvqQlIaZSxEamk4zczvnOv8w0/z/LI5WB/Teueec7zv3nvPf//wCMYrzbZmtt02UeoE1kDIfEA5A0h+LaKN5G4R4ZwHupDmk662zyj2oi/xfRFYDOa6yTOnGEQmxSULao9mzXkD0CMibwoajzaVV7ZF8TAPIe783eeBjRzk5H6Adp0UCMdUJ0Uu6yuTcScebZpwbMLIzDIB37f0lbhPxQiOnuNeEqLMkyfVGpxEWQO7DjYUer+cukWTFTRTZoTVJw8oPy6teB5uFBKB27kb9CJDrnK0WG+YFn4Smazjn6tiHf+c6BY9ZzMFc+mIgAFVww5VzHd1oJA5/cSutSoG/6JqGXO1GRJHW6OmgoszjVKgT4Od8uMmTNZt5CPRYK06y0PiG40vG3Dp+zbrMJXAtPou8tMmmzszJ3Bpfr7HecKZoQYqlYwtxpmA3slImoHr+MdMgmJO5NXW3BwEkMp1ln4arsw8iSbMqmFc9H9DcZ34TM7dGuacXS+IyNWUSrs85jDTrKAX2msh3NJyGRxKNmRA3FSG/1RKTcTY7bswtx/jkDAXU0teBLc8r0OftjwIsHBSA/ko1t102rghnC/bAqLJTLaNwjXaek5qpAL4OdGPzs+P46u42BwxopGMwWYGF8El2ykScL9yH0UnpmJmeje0Np9Da36UMrcKCK0UHUJQxXf3u9fRj64sKtPw0z3swg6BK5BRQM2EuC8bkw25NVQZOew5qFp0AVzrLKecuFI+frea/fB7sfHkGXHixihTii5hyv8wFiZJITpwC/RTYzit9qP/eiIVjncpNSon9by6g+kttJJhwncAjjduocE3oSu23l1hddwiNP1qUwiK0ADkvVLy/GT85OxK3xj0cz6PJp5+dWPukHA86n4aYurpe4HJzTBAhfvyDuTVuILmHC9MaLPT73NjWcBK3Pj+i60OqS2YLFd1QhDkHucl76r2yiz5gVzxAGxzFqGmvQ5/PsNWLCkXVf6llRdVuGikV1L1SPriBjFlutT0eMjlzKU5iUwH4W6TKmNkTN6zU2zIVAONx60yR1SWOHQWBOBSX3+z/aUo5ID4Wq8W6iqat/gCHc1BtuX70OnDICeiLf/PDJFADOjmPHCXlqYRq4li8T0cwjvIlDMb6c+e6neEJ6Eoe+TT+ycdpcBA8H6nP898PW2+tnIPs1AAAAABJRU5ErkJggg==" class="bd_nd_B937DB990D1548698380D65CF906E308_icon_green" style="border: 0px; cursor: pointer; display: inline; margin-right: 3px; height: 16px; width: 16px;"></span><a href="https://l.facebook.com/l.php?u=https%3A%2F%2Fwww.instagram.com%2F&amp;h=AT0QrRgRxaPYSi-6wr1HbHfuyQeTDBSFM18FwdpAx9W4P1L8ipqSPzDcygNQW4k4VszJOzs_mukDipeJft2nOK1U7hV8c6FhCTDiaLTQfkdn3XZK7b0_KiuUGR6C07LBnCHSLUbQbSS3OdYJzRV0_g" title="Take a look at Instagram" target="_blank" rel="noopener nofollow" data-lynx-mode="asynclazy">Instagram</a></li><li><a href="https://www.bulletin.com/" title="Take a look at Bulletin newsletter">Bulletin</a></li><li><a href="/local/lists/245019872666104/" title="Browse our Local Lists directory.">Local</a></li><li><a href="/fundraisers/" title="Donate to worthy causes.">Fundraisers</a></li><li><a href="/biz/directory/" title="Browse our Facebook Services directory.">Services</a></li><li><a href="/votinginformationcenter/?entry_point=c2l0ZQ%3D%3D" title="See the Voting Information Centre">Voting Information Centre</a></li><li><a href="/groups/explore/" title="Explore our groups.">Groups</a></li><li><a href="https://about.facebook.com/" accesskey="8" title="Read our blog, discover the resource centre and find job opportunities.">About</a></li><li><a href="/ad_campaign/landing.php?placement=pflo&amp;campaign_id=402047449186&amp;nav_source=unknown&amp;extra_1=auto" title="Advertise on Facebook">Create ad</a></li><li><a href="/pages/create/?ref_type=site_footer" title="Create a Page">Create Page</a></li><li><a href="https://developers.facebook.com/?ref=pf" title="Develop on our platform.">Developers</a></li><li><a href="/careers/?ref=pf" title="Make your next career move to our brilliant company.">Careers</a></li><li><a data-nocookies="1" href="/privacy/explanation/" title="Learn about your privacy and Facebook.">Privacy</a></li><li><a href="/policies/cookies/" title="Learn about cookies and Facebook." data-nocookies="1">Cookies</a></li><li><a class="_41ug" data-nocookies="1" href="https://www.facebook.com/help/568137493302217" title="Learn about AdChoices.">AdChoices<i class="img sp_AcVttjh25zD sx_3feebe"></i></a></li><li><a data-nocookies="1" href="/policies?ref=pf" accesskey="9" title="Review our terms and policies.">Terms</a></li><li><a href="/help/?ref=pf" accesskey="0" title="Visit our Help Centre.">Help</a></li><li><a accesskey="6" class="accessible_elem" href="/settings" title="View and edit your Facebook settings.">Settings</a></li><li><a accesskey="7" class="accessible_elem" href="/allactivity?privacy_source=activity_log_top_menu" title="View your activity log">Activity log</a></li></ul></div><div class="mvl copyright"><div><span> Meta © 2022</span></div></div></div></div></div></div><div></div><span><img src="https://facebook.com/security/hsts-pixel.gif" width="0" height="0" style="display:none"></span></div><div style="display:none"></div>
<script>requireLazy(["HasteSupportData"],function(m){m.handle({"bxData":{"875231":{"uri":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/yD\/r\/d4ZIVX-5C-b.ico"}},"gkxData":{"4166":{"result":false,"hash":"AT7yrb5QuQ92736ubBA"},"677762":{"result":true,"hash":"AT6e9MvRyXpacwOY5V4"},"1908135":{"result":false,"hash":"AT6miGypJl3m2Aq46nM"},"3959":{"result":true,"hash":"AT5An4B4pPVNHiK81NA"},"524":{"result":false,"hash":"AT6SLNReg1ijh3bZnPs"},"819236":{"result":false,"hash":"AT66vW86d2uJ-kXPUH8"},"12":{"result":false,"hash":"AT7MdxfOMhMQYcz01W4"},"1646":{"result":false,"hash":"AT4QD7x1GFNYajJZ4TU"},"3521":{"result":true,"hash":"AT6JXdAr_AL9yUh_4Mw"},"729631":{"result":false,"hash":"AT7b0tj8AHWG5lTFeMI"},"1281505":{"result":false,"hash":"AT4PHZM9gFoypCjQ0mQ"},"1291023":{"result":false,"hash":"AT519LseIG1nwq3o7L4"},"1294182":{"result":false,"hash":"AT4vd6mwrtAJouEJv0c"},"1399218":{"result":true,"hash":"AT6guCW1eyIkOV1EXEg"},"1401060":{"result":true,"hash":"AT5aetN5Gb3reIXVN9Q"},"1485055":{"result":true,"hash":"AT5lkGxmhfrVKlcn9FA"},"1596063":{"result":false,"hash":"AT7JHuDWtaOqRuBUobI"},"1597642":{"result":true,"hash":"AT78G4fDXhlnMl7oTG8"},"1647260":{"result":false,"hash":"AT4WdkrQSGE5dIsETF0"},"1695831":{"result":false,"hash":"AT7RA6TJmDFGF-D6Ons"},"1722014":{"result":false,"hash":"AT6_M5gpc6RLrHjcTg8"},"1742795":{"result":false,"hash":"AT6dbnY5JZm_bTINOaw"},"1778302":{"result":false,"hash":"AT65fisZhmc2X92EoeM"},"1840809":{"result":false,"hash":"AT5nYctoTsr7alRiN1M"},"1848749":{"result":false,"hash":"AT5GsH9Kb-3W-taZBao"},"1906871":{"result":false,"hash":"AT6dIBiVv9bUDXlm9Ys"},"1985945":{"result":true,"hash":"AT66Oo5lY__5wUTplj4"},"5541":{"result":true,"hash":"AT70V-Q_zfEykznO9I8"},"1099893":{"result":false,"hash":"AT5kly2LSZV_DKGReJw"}},"qexData":{"644":{"r":null},"647":{"r":null},"648":{"r":null},"650":{"r":null},"651":{"r":null}}})});requireLazy(["Bootloader"],function(m){m.handlePayload({"consistency":{"rev":1005260860},"rsrcMap":{"i4ulAqS":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yZ\/r\/Jhvid9xmsdT.js?_nc_x=Ij3Wp8lg5Kz"},"SJt9b58":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yK\/r\/28qx5chKB37.js?_nc_x=Ij3Wp8lg5Kz"},"WW8fqVn":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3ij9m4\/y2\/l\/en_GB\/IRVL8mwJYmC.js?_nc_x=Ij3Wp8lg5Kz"},"VJBByUf":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yr\/r\/yYxqF7t4UC4.js?_nc_x=Ij3Wp8lg5Kz"},"foxoXrn":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y6\/r\/04MM-wufnk2.js?_nc_x=Ij3Wp8lg5Kz"},"ZjF9HpG":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iCwx4\/y8\/l\/en_GB\/HiZbSfs0RcK.js?_nc_x=Ij3Wp8lg5Kz"},"7xieS14":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3i3674\/yI\/l\/en_GB\/54_EE3F38vK.js?_nc_x=Ij3Wp8lg5Kz"},"kCH74Pf":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yr\/r\/WsDmdtCAV2M.js?_nc_x=Ij3Wp8lg5Kz"},"VYX+Uc1":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yj\/r\/ylQZGjtoTZS.js?_nc_x=Ij3Wp8lg5Kz"},"00Aws6K":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yU\/r\/BwlkRv7B4IH.js?_nc_x=Ij3Wp8lg5Kz"},"DBscvUB":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y2\/r\/S2KfZ4m1DXF.js?_nc_x=Ij3Wp8lg5Kz"},"2\/maQ\/Q":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yL\/r\/mPQTxAVB7AK.js?_nc_x=Ij3Wp8lg5Kz"},"2CbDRJL":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yU\/r\/wIj-E6Prut5.js?_nc_x=Ij3Wp8lg5Kz"},"40kseEG":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yE\/r\/tEc5sUlhDfz.js?_nc_x=Ij3Wp8lg5Kz"},"h3A96RM":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yY\/r\/dhKWcQzymk8.js?_nc_x=Ij3Wp8lg5Kz"},"DArYdIE":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yn\/r\/yW4xJArCb1U.js?_nc_x=Ij3Wp8lg5Kz"},"TDbeFtl":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yW\/r\/6wpkzLV7sfC.js?_nc_x=Ij3Wp8lg5Kz"},"Ptj\/28Z":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iPIv4\/yG\/l\/en_GB\/e26TjiewWls.js?_nc_x=Ij3Wp8lg5Kz"},"CGkH4FY":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yZ\/r\/x4Eyp9nQ1uk.js?_nc_x=Ij3Wp8lg5Kz"},"dtBHfNn":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y5\/r\/ruBIfAyOqFt.js?_nc_x=Ij3Wp8lg5Kz"},"56VCh9H":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iFJJ4\/yX\/l\/en_GB\/Gcdqi7dvOG_.js?_nc_x=Ij3Wp8lg5Kz"},"lCiWnqM":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iNEW4\/yQ\/l\/en_GB\/7SXfmyLRrBz.js?_nc_x=Ij3Wp8lg5Kz"},"lrZhROy":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iH_P4\/y3\/l\/en_GB\/ksyKXOfpDNj.js?_nc_x=Ij3Wp8lg5Kz"},"FJvGK\/j":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yc\/l\/0,cross\/bgknk2CG-aR.css?_nc_x=Ij3Wp8lg5Kz"},"qfVP2Mx":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iLl54\/yF\/l\/en_GB\/kibHdK-L1SK.js?_nc_x=Ij3Wp8lg5Kz"},"O47flqQ":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y8\/r\/-JEw1xRrb3s.js?_nc_x=Ij3Wp8lg5Kz"},"0VY7AKa":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y5\/r\/gvUZGXfxkVz.js?_nc_x=Ij3Wp8lg5Kz"},"eLfegN8":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iTQy4\/yP\/l\/en_GB\/5vD8jQTXrjP.js?_nc_x=Ij3Wp8lg5Kz"},"RwNGFt8":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yR\/r\/NTBXcpfVOaa.js?_nc_x=Ij3Wp8lg5Kz"},"i89GxPT":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y3\/l\/0,cross\/Rh9cWFTXkKC.css?_nc_x=Ij3Wp8lg5Kz"},"IyhltvU":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iAgG4\/yc\/l\/en_GB\/fb1fmUDrgcm.js?_nc_x=Ij3Wp8lg5Kz"},"YxYiZwp":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yL\/r\/nxPyH1mHagF.js?_nc_x=Ij3Wp8lg5Kz"},"mDyabti":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y4\/r\/mEzagDJWUSz.js?_nc_x=Ij3Wp8lg5Kz"},"Pqu4AWc":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yO\/r\/BDTmsNOJeKK.js?_nc_x=Ij3Wp8lg5Kz"},"\/zbxQ3F":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/ys\/r\/XaJzqdSJ5Ez.js?_nc_x=Ij3Wp8lg5Kz"},"45g2zGz":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yN\/r\/g2e1F4SS2Pz.js?_nc_x=Ij3Wp8lg5Kz"},"flND0HS":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3idBq4\/y4\/l\/en_GB\/cE-SgBJJV_B.js?_nc_x=Ij3Wp8lg5Kz"},"\/KQiREt":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yY\/r\/POHa90_6YQ_.js?_nc_x=Ij3Wp8lg5Kz"},"wBnHkAZ":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yE\/r\/oufs3Uw-tgc.js?_nc_x=Ij3Wp8lg5Kz"},"5CEHaQA":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yW\/r\/AEzcq-6dHIE.js?_nc_x=Ij3Wp8lg5Kz"},"jKXv1s2":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iZcV4\/yD\/l\/en_GB\/3vepGXopMLA.js?_nc_x=Ij3Wp8lg5Kz"},"SmFM0mM":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iZF64\/yu\/l\/en_GB\/ZyanwiSUV2O.js?_nc_x=Ij3Wp8lg5Kz"},"tKNDETG":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yo\/r\/eIUAd_XjHmi.js?_nc_x=Ij3Wp8lg5Kz"},"Dd\/u7OF":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yb\/r\/FNpu3T3yR4F.js?_nc_x=Ij3Wp8lg5Kz"},"DmkByrt":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3is9r4\/yX\/l\/en_GB\/rZWt2X_jZkU.js?_nc_x=Ij3Wp8lg5Kz"},"PAr9NV8":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iXGq4\/y5\/l\/en_GB\/YU1M5CjXCBj.js?_nc_x=Ij3Wp8lg5Kz"},"Dg0yxcL":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3ikxI4\/yw\/l\/en_GB\/3rkRs44PP7w.js?_nc_x=Ij3Wp8lg5Kz"},"zPJqoID":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iwdk4\/y9\/l\/en_GB\/g54u2ldZWwQ.js?_nc_x=Ij3Wp8lg5Kz"},"KnHLe0g":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yh\/r\/psqTZsD9TIF.js?_nc_x=Ij3Wp8lg5Kz"},"6Xe9Ood":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y9\/l\/0,cross\/tuffxds-KQm.css?_nc_x=Ij3Wp8lg5Kz"},"ZYpmbqB":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y1\/l\/0,cross\/2lHgRFGwfIH.css?_nc_x=Ij3Wp8lg5Kz"},"yUHm+ca":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yH\/r\/K-6M7Qcy9tg.js?_nc_x=Ij3Wp8lg5Kz"},"Q\/Psu3x":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3ipaT4\/yu\/l\/en_GB\/0KbheqrLGGB.js?_nc_x=Ij3Wp8lg5Kz"},"xO06VLK":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yt\/r\/NiMhI8TA3eX.js?_nc_x=Ij3Wp8lg5Kz"},"LHrFeMg":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yW\/l\/0,cross\/YdZAAC-cM9N.css?_nc_x=Ij3Wp8lg5Kz"},"Q0KMKi+":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3ihHI4\/yN\/l\/en_GB\/dHxa0qhN9fL.js?_nc_x=Ij3Wp8lg5Kz"},"AFtrZIU":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iTbo4\/yt\/l\/en_GB\/eExlyLflPHZ.js?_nc_x=Ij3Wp8lg5Kz"},"Uy0qypv":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yr\/r\/mQmB4z8wFsu.js?_nc_x=Ij3Wp8lg5Kz"},"kp3aIVk":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y4\/r\/xwxmIzcB_x_.js?_nc_x=Ij3Wp8lg5Kz"},"NfLz6Ds":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yh\/l\/0,cross\/8RjDb6JHxbO.css?_nc_x=Ij3Wp8lg5Kz"},"TuiPcIO":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yA\/l\/0,cross\/OUw2QIwWBFP.css?_nc_x=Ij3Wp8lg5Kz"},"broVqXw":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yI\/l\/0,cross\/stit-zoInNF.css?_nc_x=Ij3Wp8lg5Kz"},"rVKs1ll":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yd\/l\/0,cross\/mtFliUFUUvI.css?_nc_x=Ij3Wp8lg5Kz"},"cnvoLNi":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iW4s4\/y3\/l\/en_GB\/O-us5GJCQW8.js?_nc_x=Ij3Wp8lg5Kz"},"gcDYlM2":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/ym\/r\/HLBoQQWMP5x.js?_nc_x=Ij3Wp8lg5Kz"},"SMSJk0U":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y4\/l\/0,cross\/7bdn49W6uV7.css?_nc_x=Ij3Wp8lg5Kz"},"sZXmT5E":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yM\/l\/0,cross\/wUQFCPJQWYh.css?_nc_x=Ij3Wp8lg5Kz"},"jj29UZB":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yE\/r\/w5W7kbBpKe-.js?_nc_x=Ij3Wp8lg5Kz"},"tTaQiwY":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3i1A04\/yJ\/l\/en_GB\/yIFIbOntWN3.js?_nc_x=Ij3Wp8lg5Kz"},"4PSYv6P":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iQXN4\/y7\/l\/en_GB\/e3nwIG9KGKe.js?_nc_x=Ij3Wp8lg5Kz"},"4Mhs36H":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y2\/r\/AYhelctm0HF.js?_nc_x=Ij3Wp8lg5Kz"},"pBZA4F9":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yb\/l\/0,cross\/tWBvPir7ARu.css?_nc_x=Ij3Wp8lg5Kz"},"aF9iPHd":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iLl54\/yi\/l\/en_GB\/yMzqnohiu7a.js?_nc_x=Ij3Wp8lg5Kz"},"SrpP6vx":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yx\/r\/bll4-7p4Ipj.js?_nc_x=Ij3Wp8lg5Kz"},"KQ4v1EB":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yA\/r\/Q9879mLKLWA.js?_nc_x=Ij3Wp8lg5Kz"},"GQaWz8T":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yn\/r\/ngE_0xyFwgy.js?_nc_x=Ij3Wp8lg5Kz"},"9jeSk45":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iFVC4\/yD\/l\/en_GB\/SCBWxoK-dMc.js?_nc_x=Ij3Wp8lg5Kz"},"ImV+4xA":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yG\/l\/0,cross\/j8soV1cc3bh.css?_nc_x=Ij3Wp8lg5Kz"},"yNMBDvx":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yC\/l\/0,cross\/liweRJSO0NM.css?_nc_x=Ij3Wp8lg5Kz"},"AttAnNB":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y3\/r\/2OsKHpJLib_.js?_nc_x=Ij3Wp8lg5Kz"},"YXEtucs":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yM\/l\/0,cross\/d3laCPZwHw0.css?_nc_x=Ij3Wp8lg5Kz"},"Sl4ibjZ":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yg\/r\/nedVQAeVb8c.js?_nc_x=Ij3Wp8lg5Kz"},"TXkrFHb":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3i_QL4\/ya\/l\/en_GB\/eHun_SLLSsV.js?_nc_x=Ij3Wp8lg5Kz"},"fOwQG8c":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yF\/r\/xx-KeT70Cwa.js?_nc_x=Ij3Wp8lg5Kz"},"DOztrZP":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/ya\/l\/0,cross\/ImCrkv64rxO.css?_nc_x=Ij3Wp8lg5Kz"},"V7XUlmC":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y9\/l\/0,cross\/mbZ4n-06MtY.css?_nc_x=Ij3Wp8lg5Kz"},"xXr6omd":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3ievZ4\/y-\/l\/en_GB\/Y_-GYndmwoP.js?_nc_x=Ij3Wp8lg5Kz"},"X\/qujF4":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3i9ar4\/yE\/l\/en_GB\/ZQs17z2yQMh.js?_nc_x=Ij3Wp8lg5Kz"},"OQcjTC8":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iTSN4\/yV\/l\/en_GB\/eIkrdMLsd6m.js?_nc_x=Ij3Wp8lg5Kz"},"Kbl+CEt":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3ip-t4\/yz\/l\/en_GB\/98Kavp0klE0.js?_nc_x=Ij3Wp8lg5Kz"},"UrWni7N":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3i8NL4\/y4\/l\/en_GB\/BNKIsxxNDvm.js?_nc_x=Ij3Wp8lg5Kz"},"+822EEJ":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yO\/r\/novga5l74Nd.js?_nc_x=Ij3Wp8lg5Kz"},"D7WvREQ":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yv\/r\/hqloCTUBQq5.js?_nc_x=Ij3Wp8lg5Kz"},"ovx4rrL":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3i4EL4\/y2\/l\/en_GB\/E4cUm8xfNxe.js?_nc_x=Ij3Wp8lg5Kz"},"NaRov2Z":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3i7xv4\/yH\/l\/en_GB\/iecet726DmQ.js?_nc_x=Ij3Wp8lg5Kz"},"eSpBqcn":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yN\/r\/w70UYVEps0P.js?_nc_x=Ij3Wp8lg5Kz"},"zBSBK40":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iLKP4\/yp\/l\/en_GB\/7M5qv9p_gGa.js?_nc_x=Ij3Wp8lg5Kz"},"8qIjNFg":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3itci4\/yV\/l\/en_GB\/mw5SuCrT6nK.js?_nc_x=Ij3Wp8lg5Kz"},"HvMFJzQ":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iHTt4\/yU\/l\/en_GB\/xS5fQb4lGQk.js?_nc_x=Ij3Wp8lg5Kz"},"xP1R8CA":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iLl54\/yk\/l\/en_GB\/49OPtPTfUsZ.js?_nc_x=Ij3Wp8lg5Kz"},"mwb\/Y8O":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iAiU4\/yp\/l\/en_GB\/g0dUUAfcnAm.js?_nc_x=Ij3Wp8lg5Kz"},"A63vnnR":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yO\/r\/TRf0FciNAyh.js?_nc_x=Ij3Wp8lg5Kz"},"lRnn76M":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3ibcU4\/yg\/l\/en_GB\/u61rXN4xtun.js?_nc_x=Ij3Wp8lg5Kz"},"mnKy\/Yn":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3im6d4\/yX\/l\/en_GB\/NhPm-ppNG0w.js?_nc_x=Ij3Wp8lg5Kz"},"lB9jH3b":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y9\/l\/0,cross\/mqOPJv6q6ah.css?_nc_x=Ij3Wp8lg5Kz"},"gWMJgTe":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yH\/r\/iGksp69foR_.js?_nc_x=Ij3Wp8lg5Kz"},"hIek+bG":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yY\/r\/DZ_VBlsy-dC.js?_nc_x=Ij3Wp8lg5Kz"},"IPmrcSF":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yx\/r\/_g_ktPAPYvP.js?_nc_x=Ij3Wp8lg5Kz"},"xIwdAub":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iTfb4\/y2\/l\/en_GB\/IR4cYaPMw1j.js?_nc_x=Ij3Wp8lg5Kz"},"dcLZ7lC":{"type":"css","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y-\/l\/0,cross\/93pgEjMSnoq.css?_nc_x=Ij3Wp8lg5Kz"},"8ELCBwH":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/ye\/r\/VRzSVH5iU-V.js?_nc_x=Ij3Wp8lg5Kz"},"sqdif1t":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3iuMX4\/yg\/l\/en_GB\/IX8d3VCxdS7.js?_nc_x=Ij3Wp8lg5Kz"},"SWx3yNv":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yW\/r\/O_SjdcR-xKL.js?_nc_x=Ij3Wp8lg5Kz"},"x22Oby4":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/y0\/r\/fN3cCj7Il4D.js?_nc_x=Ij3Wp8lg5Kz"},"oE4DofT":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yJ\/r\/EejAgnHUad4.js?_nc_x=Ij3Wp8lg5Kz"},"VvVFw8n":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yn\/r\/AWepvf-vdZG.js?_nc_x=Ij3Wp8lg5Kz"},"1Rv\/+Xz":{"type":"js","src":"https:\/\/static.xx.fbcdn.net\/rsrc.php\/v3\/yu\/r\/XaPDIOxwUYb.js?_nc_x=Ij3Wp8lg5Kz"},"P\/mr5VE":{"type":"css","src":"data:text\/css; charset=utf-8,\u002523bootloader_P_mr5VE{height:42px;}.bootloader_P_mr5VE{display:block!important;}","nc":1,"d":1}},"compMap":{"ODS":{"r":["i4ulAqS"],"be":1},"Dock":{"r":["T\/eaVKH","SJt9b58","WW8fqVn","VJBByUf","vi\/i3HE","foxoXrn","i4ulAqS","ZjF9HpG","7xieS14"],"be":1},"WebSpeedInteractionsTypedLogger":{"r":["kCH74Pf","i4ulAqS","VYX+Uc1"],"rds":{"m":["BanzaiScuba_DEPRECATED"]},"be":1},"AsyncRequest":{"r":["SJt9b58","WW8fqVn","00Aws6K","foxoXrn","i4ulAqS","T\/eaVKH"],"rds":{"m":["FbtLogging","IntlQtEventFalcoEvent"],"r":["7xieS14"]},"be":1},"DOM":{"r":["SJt9b58","foxoXrn","T\/eaVKH"],"be":1},"Form":{"r":["SJt9b58","foxoXrn","ZjF9HpG","T\/eaVKH"],"be":1},"FormSubmit":{"r":["SJt9b58","WW8fqVn","00Aws6K","foxoXrn","i4ulAqS","DBscvUB","ZjF9HpG","T\/eaVKH"],"rds":{"m":["FbtLogging","IntlQtEventFalcoEvent","BanzaiScuba_DEPRECATED"],"r":["7xieS14"]},"be":1},"Input":{"r":["ZjF9HpG"],"be":1},"Live":{"r":["2\/maQ\/Q","2CbDRJL","SJt9b58","WW8fqVn","40kseEG","foxoXrn","i4ulAqS","T\/eaVKH"],"be":1},"Toggler":{"r":["T\/eaVKH","SJt9b58","WW8fqVn","VJBByUf","vi\/i3HE","foxoXrn","i4ulAqS","ZjF9HpG","7xieS14"],"be":1},"Tooltip":{"r":["h3A96RM","T\/eaVKH","DArYdIE","SJt9b58","WW8fqVn","TDbeFtl","Ptj\/28Z","00Aws6K","VJBByUf","CGkH4FY","27iTcKo","foxoXrn","i4ulAqS","ZjF9HpG","7xieS14","dtBHfNn","VYX+Uc1"],"rds":{"m":["FbtLogging","IntlQtEventFalcoEvent","PageTransitions","BanzaiScuba_DEPRECATED","Animation"]},"be":1},"URI":{"r":[],"be":1},"trackReferrer":{"r":[],"rds":{"m":["BanzaiScuba_DEPRECATED"],"r":["i4ulAqS"]},"be":1},"PhotoTagApproval":{"r":["SJt9b58","56VCh9H","lCiWnqM","foxoXrn","T\/eaVKH"],"be":1},"PhotoSnowlift":{"r":["lrZhROy","FJvGK\/j","XGDA5to","h3A96RM","T\/eaVKH","qfVP2Mx","O47flqQ","0VY7AKa","2CbDRJL","eLfegN8","RwNGFt8","i89GxPT","IyhltvU","YxYiZwp","mDyabti","Pqu4AWc","\/zbxQ3F","DArYdIE","SJt9b58","45g2zGz","WW8fqVn","TDbeFtl","flND0HS","Ptj\/28Z","\/KQiREt","lCiWnqM","00Aws6K","wBnHkAZ","VJBByUf","5CEHaQA","40kseEG","CGkH4FY","jKXv1s2","SmFM0mM","tKNDETG","vi\/i3HE","Dd\/u7OF","DmkByrt","VYX+Uc1","PAr9NV8","27iTcKo","Dg0yxcL","zPJqoID","KnHLe0g","6Xe9Ood","foxoXrn","i4ulAqS","ZYpmbqB","yUHm+ca","ZjF9HpG","7xieS14","Q\/Psu3x","xO06VLK","LHrFeMg","Q0KMKi+","dtBHfNn"],"rds":{"m":["Animation","VisualCompletionGating","FbtLogging","IntlQtEventFalcoEvent","BanzaiScuba_DEPRECATED","PageTransitions"]},"be":1},"PhotoTagger":{"r":["AFtrZIU","lrZhROy","Uy0qypv","kp3aIVk","FJvGK\/j","NfLz6Ds","XGDA5to","h3A96RM","T\/eaVKH","qfVP2Mx","TuiPcIO","0VY7AKa","2CbDRJL","eLfegN8","RwNGFt8","broVqXw","rVKs1ll","IyhltvU","YxYiZwp","mDyabti","cnvoLNi","gcDYlM2","SMSJk0U","Pqu4AWc","sZXmT5E","\/zbxQ3F","DArYdIE","jj29UZB","tTaQiwY","4PSYv6P","SJt9b58","45g2zGz","4Mhs36H","56VCh9H","WW8fqVn","TDbeFtl","Ptj\/28Z","\/KQiREt","pBZA4F9","aF9iPHd","SrpP6vx","lCiWnqM","00Aws6K","wBnHkAZ","KQ4v1EB","VJBByUf","5CEHaQA","40kseEG","GQaWz8T","9jeSk45","CGkH4FY","ImV+4xA","jKXv1s2","SmFM0mM","tKNDETG","vi\/i3HE","Dd\/u7OF","VYX+Uc1","yNMBDvx","AttAnNB","27iTcKo","YXEtucs","zPJqoID","KnHLe0g","foxoXrn","Sl4ibjZ","TXkrFHb","fOwQG8c","i4ulAqS","ZYpmbqB","DOztrZP","ZjF9HpG","V7XUlmC","xXr6omd","X\/qujF4","OQcjTC8","Kbl+CEt","7xieS14","UrWni7N","Q\/Psu3x","xO06VLK","+822EEJ","Q0KMKi+","dtBHfNn","D7WvREQ","ovx4rrL","NaRov2Z"],"rdfds":{"m":["GamesVideoModerationRulesNux.react","GamesVideoDeleteCommentDialog.react","GamesVideoCommentRemovedDialog.react","CometTooltipDeferredImpl.react"],"r":["eSpBqcn","i89GxPT","zBSBK40","8qIjNFg","HvMFJzQ","xP1R8CA","mwb\/Y8O","A63vnnR"]},"rds":{"m":["PresenceStatus","FbtLogging","IntlQtEventFalcoEvent","BanzaiScuba_DEPRECATED","Animation","PageTransitions","LynxAsyncCallbackFalcoEvent","CometSuspenseFalcoEvent"],"r":["lRnn76M"]},"be":1},"PhotoTags":{"r":["SJt9b58","56VCh9H","lCiWnqM","foxoXrn","ZjF9HpG","T\/eaVKH"],"be":1},"TagTokenizer":{"r":["XGDA5to","T\/eaVKH","RwNGFt8","broVqXw","mnKy\/Yn","SJt9b58","56VCh9H","PAr9NV8","Dg0yxcL","lB9jH3b","foxoXrn","i4ulAqS","ZjF9HpG"],"rds":{"m":["FbtLogging","IntlQtEventFalcoEvent"],"r":["7xieS14"]},"be":1},"AsyncDialog":{"r":["XGDA5to","h3A96RM","T\/eaVKH","qfVP2Mx","YxYiZwp","SJt9b58","WW8fqVn","TDbeFtl","Ptj\/28Z","00Aws6K","VJBByUf","vi\/i3HE","Dd\/u7OF","foxoXrn","i4ulAqS","ZjF9HpG","7xieS14","dtBHfNn","VYX+Uc1"],"rds":{"m":["FbtLogging","IntlQtEventFalcoEvent"]},"be":1},"Hovercard":{"r":["XGDA5to","h3A96RM","T\/eaVKH","SMSJk0U","DArYdIE","SJt9b58","WW8fqVn","TDbeFtl","Ptj\/28Z","aF9iPHd","00Aws6K","VJBByUf","CGkH4FY","ImV+4xA","vi\/i3HE","VYX+Uc1","27iTcKo","foxoXrn","fOwQG8c","i4ulAqS","ZYpmbqB","ZjF9HpG","7xieS14","Q0KMKi+","dtBHfNn"],"rds":{"m":["FbtLogging","IntlQtEventFalcoEvent","BanzaiScuba_DEPRECATED","PageTransitions","Animation"]},"be":1},"XSalesPromoWWWDetailsDialogAsyncController":{"r":["gWMJgTe"],"be":1},"XOfferController":{"r":["hIek+bG"],"be":1},"PerfXSharedFields":{"r":["i4ulAqS"],"be":1},"KeyEventTypedLogger":{"r":["IPmrcSF","i4ulAqS","VYX+Uc1"],"rds":{"m":["BanzaiScuba_DEPRECATED"]},"be":1},"Dialog":{"r":["T\/eaVKH","eLfegN8","SJt9b58","WW8fqVn","00Aws6K","VJBByUf","vi\/i3HE","foxoXrn","i4ulAqS","ZYpmbqB","ZjF9HpG","7xieS14","h3A96RM","VYX+Uc1"],"rds":{"m":["FbtLogging","IntlQtEventFalcoEvent","Animation","PageTransitions","BanzaiScuba_DEPRECATED"]},"be":1},"ExceptionDialog":{"r":["lrZhROy","XGDA5to","h3A96RM","T\/eaVKH","qfVP2Mx","YxYiZwp","SJt9b58","WW8fqVn","TDbeFtl","Ptj\/28Z","00Aws6K","VJBByUf","SmFM0mM","vi\/i3HE","Dd\/u7OF","zPJqoID","xIwdAub","foxoXrn","i4ulAqS","dcLZ7lC","ZjF9HpG","7xieS14","dtBHfNn","VYX+Uc1"],"rds":{"m":["FbtLogging","IntlQtEventFalcoEvent"]},"be":1},"QuickSandSolver":{"r":["8ELCBwH","SJt9b58","sqdif1t","WW8fqVn","00Aws6K","KnHLe0g","foxoXrn","i4ulAqS","SWx3yNv","ZjF9HpG","x22Oby4","T\/eaVKH"],"rds":{"m":["FbtLogging","IntlQtEventFalcoEvent"],"r":["7xieS14"]},"be":1},"ConfirmationDialog":{"r":["SJt9b58","oE4DofT","foxoXrn","ZjF9HpG","T\/eaVKH"],"be":1},"QPLInspector":{"r":["VvVFw8n"],"be":1},"ReactDOM":{"r":["h3A96RM","VYX+Uc1","dtBHfNn","foxoXrn","T\/eaVKH"],"be":1},"ContextualLayerInlineTabOrder":{"r":["T\/eaVKH","SJt9b58","TDbeFtl","foxoXrn","fOwQG8c","ZjF9HpG","7xieS14"],"be":1},"XUIDialogButton.react":{"r":["lrZhROy","XGDA5to","h3A96RM","T\/eaVKH","qfVP2Mx","YxYiZwp","SJt9b58","WW8fqVn","TDbeFtl","00Aws6K","VJBByUf","SmFM0mM","vi\/i3HE","Dd\/u7OF","foxoXrn","i4ulAqS","ZjF9HpG","dtBHfNn","VYX+Uc1"],"rds":{"m":["FbtLogging","IntlQtEventFalcoEvent"],"r":["7xieS14"]},"be":1},"XUIDialogBody.react":{"r":["XGDA5to","h3A96RM","TDbeFtl","VJBByUf","SmFM0mM","vi\/i3HE","foxoXrn","dtBHfNn","VYX+Uc1","i4ulAqS"],"be":1},"XUIDialogFooter.react":{"r":["XGDA5to","h3A96RM","qfVP2Mx","TDbeFtl","VJBByUf","SmFM0mM","vi\/i3HE","foxoXrn","dcLZ7lC","dtBHfNn","VYX+Uc1","i4ulAqS"],"be":1},"XUIDialogTitle.react":{"r":["h3A96RM","qfVP2Mx","SJt9b58","WW8fqVn","TDbeFtl","Ptj\/28Z","00Aws6K","VJBByUf","vi\/i3HE","foxoXrn","i4ulAqS","dtBHfNn","T\/eaVKH","VYX+Uc1"],"rds":{"m":["FbtLogging","IntlQtEventFalcoEvent"],"r":["7xieS14"]},"be":1},"XUIGrayText.react":{"r":["XGDA5to","h3A96RM","TDbeFtl","VJBByUf","SmFM0mM","foxoXrn","dtBHfNn","VYX+Uc1","i4ulAqS"],"be":1},"DialogX":{"r":["T\/eaVKH","SJt9b58","WW8fqVn","Ptj\/28Z","VJBByUf","vi\/i3HE","foxoXrn","i4ulAqS","ZjF9HpG","7xieS14"],"rds":{"m":["FbtLogging","IntlQtEventFalcoEvent"]},"be":1},"React":{"r":["h3A96RM","VYX+Uc1"],"be":1}}})});</script>
<script>requireLazy(["InitialJSLoader"], function(InitialJSLoader) {InitialJSLoader.loadOnDOMContentReady(["WW8fqVn","1Rv\/+Xz","TDbeFtl","7xieS14","ZjF9HpG","SJt9b58","VJBByUf","i4ulAqS","00Aws6K","foxoXrn","h3A96RM","DArYdIE","CGkH4FY","VYX+Uc1","dtBHfNn","P\/mr5VE"]);});</script>
<script>requireLazy(["TimeSliceImpl","ServerJS"],function(TimeSlice,ServerJS){var s=(new ServerJS());s.handle({"define":[["LinkshimHandlerConfig",[],{"supports_meta_referrer":true,"default_meta_referrer_policy":"origin-when-crossorigin","switched_meta_referrer_policy":"origin","non_linkshim_lnfb_mode":null,"link_react_default_hash":"AT1PqOg7HseRnqKN2iSLyTyyIM1FqbCtLL0M5BsBXI5fkndVebLnJpGhsTytQ2LcJLlhPf7k_Nwo-__geEj9abzLL3vxqLgSwCaqmpHtUthauygyvHU94OLjcxCrIuBS1dGDJ-Eoh6Rr0yluD6Xj4w","untrusted_link_default_hash":"AT3ts-WRcwVk4ne9CCND8wCKCa4IeDskdK2q97cP7rSodzcmyI0-BZsGtWjEzn-0QMucA3BgvSfJDCxWoo2O5vhPO9qzpXrHk1cxJ_CItYtZHOho5YLMttTVGnJOpmyA-7a9p8TLsYzM3fHrqGEwDw","linkshim_host":"l.facebook.com","linkshim_path":"\/l.php","linkshim_enc_param":"h","linkshim_url_param":"u","use_rel_no_opener":true,"always_use_https":true,"onion_always_shim":true,"middle_click_requires_event":true,"www_safe_js_mode":"asynclazy","m_safe_js_mode":"MLynx_asynclazy","ghl_param_link_shim":false,"click_ids":[],"is_linkshim_supported":true,"current_domain":"facebook.com","blocklisted_domains":["ad.doubleclick.net","ads-encryption-url-example.com","bs.serving-sys.com","ad.atdmt.com","adform.net","ad13.adfarm1.adition.com","ilovemyfreedoms.com","secure.adnxs.com"],"is_mobile_device":false},27]],"instances":[["__inst_5b4d0c00_0_0_b4",["Menu","XUIMenuWithSquareCorner","XUIMenuTheme"],[[],{"id":"u_0_0_qO","behaviors":[{"__m":"XUIMenuWithSquareCorner"}],"theme":{"__m":"XUIMenuTheme"}}],2],["__inst_5b4d0c00_0_1_eP",["Menu","MenuItem","__markup_3310c079_0_0_Uv","HTML","__markup_3310c079_0_1_cK","__markup_3310c079_0_2_Ax","__markup_3310c079_0_3_gu","XUIMenuWithSquareCorner","XUIMenuTheme"],[[{"value":"key_shortcuts","ctor":{"__m":"MenuItem"},"markup":{"__m":"__markup_3310c079_0_0_Uv"},"label":"Keyboard shortcut help...","title":"","className":null},{"href":"\/help\/accessibility","target":"_blank","value":"help_center","ctor":{"__m":"MenuItem"},"markup":{"__m":"__markup_3310c079_0_1_cK"},"label":"Accessibility Help Centre","title":"","className":null},{"href":"\/help\/contact\/accessibility","target":"_blank","value":"submit_feedback","ctor":{"__m":"MenuItem"},"markup":{"__m":"__markup_3310c079_0_2_Ax"},"label":"Submit feedback","title":"","className":null},{"href":"\/accessibility","target":"_blank","value":"facebook_page","ctor":{"__m":"MenuItem"},"markup":{"__m":"__markup_3310c079_0_3_gu"},"label":"Updates from Facebook Accessibility","title":"","className":null}],{"id":"u_0_1_wG","behaviors":[{"__m":"XUIMenuWithSquareCorner"}],"theme":{"__m":"XUIMenuTheme"}}],2],["__inst_e5ad243d_0_0_Lf",["PopoverMenu","__inst_1de146dc_0_1_qb","__elem_ec77afbd_0_1_R4","__inst_5b4d0c00_0_1_eP"],[{"__m":"__inst_1de146dc_0_1_qb"},{"__m":"__elem_ec77afbd_0_1_R4"},{"__m":"__inst_5b4d0c00_0_1_eP"},[]],2],["__inst_e5ad243d_0_1_5h",["PopoverMenu","__inst_1de146dc_0_0_Ow","__elem_ec77afbd_0_0_J4","__inst_5b4d0c00_0_0_b4"],[{"__m":"__inst_1de146dc_0_0_Ow"},{"__m":"__elem_ec77afbd_0_0_J4"},{"__m":"__inst_5b4d0c00_0_0_b4"},[]],2],["__inst_1de146dc_0_0_Ow",["Popover","__elem_1de146dc_0_0_6M","__elem_ec77afbd_0_0_J4","ContextualLayerAutoFlip","ContextualDialogArrow"],[{"__m":"__elem_1de146dc_0_0_6M"},{"__m":"__elem_ec77afbd_0_0_J4"},[{"__m":"ContextualLayerAutoFlip"},{"__m":"ContextualDialogArrow"}],{"alignh":"left","position":"below"}],2],["__inst_1de146dc_0_1_qb",["Popover","__elem_1de146dc_0_1_SO","__elem_ec77afbd_0_1_R4","ContextualLayerAutoFlip","ContextualDialogArrow"],[{"__m":"__elem_1de146dc_0_1_SO"},{"__m":"__elem_ec77afbd_0_1_R4"},[{"__m":"ContextualLayerAutoFlip"},{"__m":"ContextualDialogArrow"}],{"alignh":"right","position":"below"}],2]],"markup":[["__markup_3310c079_0_0_Uv",{"__html":"Keyboard shortcut help..."},1],["__markup_3310c079_0_1_cK",{"__html":"Accessibility Help Centre"},1],["__markup_3310c079_0_2_Ax",{"__html":"Submit feedback"},1],["__markup_3310c079_0_3_gu",{"__html":"Updates from Facebook Accessibility"},1]],"elements":[["__elem_a588f507_0_1_Ud","u_0_3_+7",1],["__elem_3fc3da18_0_0_br","u_0_4_Zu",1],["__elem_51be6cb7_0_0_uW","u_0_5_zW",1],["__elem_1de146dc_0_0_6M","u_0_6_MM",1],["__elem_ec77afbd_0_0_J4","u_0_7_c+",2],["__elem_1de146dc_0_1_SO","u_0_8_kd",1],["__elem_ec77afbd_0_1_R4","u_0_9_SB",2],["__elem_a588f507_0_0_mm","globalContainer",2],["__elem_a588f507_0_2_MO","content",1],["__elem_835c633a_0_0_QO","u_0_a_M3",1],["__elem_9f5fac15_0_0_wC","passContainer",1],["__elem_558608f3_0_0_rH","pass",1],["__elem_a588f507_0_3_tb","u_0_b_XT",1],["__elem_a588f507_0_4_+I","u_0_c_+V",1],["__elem_45d73b5d_0_0_uJ","u_0_d_cg",1]],"require":[["ServiceWorkerLoginAndLogout","login",[],[]],["WebPixelRatioDetector","startDetecting",[],[false]],["ScriptPath","set",[],["XIndexReduxController","a1f3c513",{"imp_id":"1xJc3qVIc4HEx2t5J","ef_page":null,"uri":"https:\/\/www.facebook.com\/"}]],["UITinyViewportAction","init",[],[]],["ResetScrollOnUnload","init",["__elem_a588f507_0_0_mm"],[{"__m":"__elem_a588f507_0_0_mm"}]],["AccessibilityWebVirtualCursorClickLogger","init",["__elem_a588f507_0_0_mm"],[[{"__m":"__elem_a588f507_0_0_mm"}]]],["KeyboardActivityLogger","init",[],[]],["FocusRing","init",[],[]],["ErrorMessageConsole","listenForUncaughtErrors",[],[]],["HardwareCSS","init",[],[]],["NavigationAssistantController","init",["__elem_3fc3da18_0_0_br","__elem_51be6cb7_0_0_uW","__inst_5b4d0c00_0_0_b4","__inst_5b4d0c00_0_1_eP","__inst_e5ad243d_0_0_Lf","__inst_e5ad243d_0_1_5h"],[{"__m":"__elem_3fc3da18_0_0_br"},{"__m":"__elem_51be6cb7_0_0_uW"},{"__m":"__inst_5b4d0c00_0_0_b4"},{"__m":"__inst_5b4d0c00_0_1_eP"},null,{"accessibilityPopoverMenu":{"__m":"__inst_e5ad243d_0_0_Lf"},"globalPopoverMenu":null,"sectionsPopoverMenu":{"__m":"__inst_e5ad243d_0_1_5h"}},true]],["__inst_e5ad243d_0_1_5h"],["__inst_1de146dc_0_0_Ow"],["__inst_e5ad243d_0_0_Lf"],["__inst_1de146dc_0_1_qb"],["LoginFormController","init",["__elem_835c633a_0_0_QO","__elem_45d73b5d_0_0_uJ"],[{"__m":"__elem_835c633a_0_0_QO"},{"__m":"__elem_45d73b5d_0_0_uJ"},null,true,{"pubKey":{"publicKey":"21e3c2e8e81a6a80fa697a484e67188659325efa6dffe4ecb3a6a1e46eec9e2f","keyId":8}}]],["BrowserPrefillLogging","initContactpointFieldLogging",[],[{"contactpointFieldID":"email","serverPrefill":""}]],["BrowserPrefillLogging","initPasswordFieldLogging",[],[{"passwordFieldID":"pass"}]],["FocusListener"],["FlipDirectionOnKeypress"],["LoginFormToggle","initToggle",["__elem_a588f507_0_3_tb","__elem_a588f507_0_4_+I","__elem_558608f3_0_0_rH","__elem_9f5fac15_0_0_wC"],[{"__m":"__elem_a588f507_0_3_tb"},{"__m":"__elem_a588f507_0_4_+I"},{"__m":"__elem_558608f3_0_0_rH"},{"__m":"__elem_9f5fac15_0_0_wC"}]],["IntlUtils"],["FBLynx","setupDelegation",[],[]],["Animation"],["PageTransitions"],["RequireDeferredReference","unblock",[],[["BanzaiScuba_DEPRECATED","Animation","FbtLogging","IntlQtEventFalcoEvent","PageTransitions"],"sd"]],["RequireDeferredReference","unblock",[],[["BanzaiScuba_DEPRECATED","Animation","FbtLogging","IntlQtEventFalcoEvent","PageTransitions"],"css"]],["TimeSliceImpl"],["HasteSupportData"],["ServerJS"],["Run"],["InitialJSLoader"]],"contexts":[[{"__m":"__elem_a588f507_0_1_Ud"},true],[{"__m":"__elem_a588f507_0_2_MO"},true]]});requireLazy(["Run"],function(Run){Run.onAfterLoad(function(){s.cleanup(TimeSlice)})});});</script>
<script>now_inl=(function(){var p=window.performance;return p&&p.now&&p.timing&&p.timing.navigationStart?function(){return p.now()+p.timing.navigationStart}:function(){return new Date().getTime()};})();window.__bigPipeFR=now_inl();</script>
<link rel="preload" href="https://static.xx.fbcdn.net/rsrc.php/v3/yL/l/0,cross/RGwypa6I2jS.css?_nc_x=Ij3Wp8lg5Kz" as="style" crossorigin="anonymous">
<link rel="preload" href="https://static.xx.fbcdn.net/rsrc.php/v3/yo/l/0,cross/Fc91FO1H-Zk.css?_nc_x=Ij3Wp8lg5Kz" as="style" crossorigin="anonymous">
<link rel="preload" href="https://static.xx.fbcdn.net/rsrc.php/v3/yg/l/0,cross/e5HhDlJHlk1.css?_nc_x=Ij3Wp8lg5Kz" as="style" crossorigin="anonymous">
<link rel="preload" href="https://static.xx.fbcdn.net/rsrc.php/v3/yD/l/0,cross/JYql2bxfGFO.css?_nc_x=Ij3Wp8lg5Kz" as="style" crossorigin="anonymous">
<link rel="preload" href="https://static.xx.fbcdn.net/rsrc.php/v3/yK/r/28qx5chKB37.js?_nc_x=Ij3Wp8lg5Kz" as="script" crossorigin="anonymous" nonce="">
<link rel="preload" href="https://static.xx.fbcdn.net/rsrc.php/v3ij9m4/y2/l/en_GB/IRVL8mwJYmC.js?_nc_x=Ij3Wp8lg5Kz" as="script" crossorigin="anonymous" nonce="">
<link rel="preload" href="https://static.xx.fbcdn.net/rsrc.php/v3/yU/r/BwlkRv7B4IH.js?_nc_x=Ij3Wp8lg5Kz" as="script" crossorigin="anonymous" nonce="">
<link rel="preload" href="https://static.xx.fbcdn.net/rsrc.php/v3/yk/l/0,cross/sPcFrnaRncH.css?_nc_x=Ij3Wp8lg5Kz" as="style" crossorigin="anonymous">
<link rel="preload" href="https://static.xx.fbcdn.net/rsrc.php/v3/y6/r/04MM-wufnk2.js?_nc_x=Ij3Wp8lg5Kz" as="script" crossorigin="anonymous" nonce="">
<link rel="preload" href="https://static.xx.fbcdn.net/rsrc.php/v3/yZ/r/Jhvid9xmsdT.js?_nc_x=Ij3Wp8lg5Kz" as="script" crossorigin="anonymous" nonce="">
<link rel="preload" href="https://static.xx.fbcdn.net/rsrc.php/v3/yF/l/0,cross/nG7XmC3cZWM.css?_nc_x=Ij3Wp8lg5Kz" as="style" crossorigin="anonymous">
<script>window.__bigPipeCtor=now_inl();requireLazy(["BigPipe"],function(BigPipe){define("__bigPipe",[],window.bigPipe=new BigPipe({"forceFinish":true,"config":{"flush_pagelets_asap":true,"dispatch_pagelet_replayable_actions":false}}));});</script>
<script nonce="">(function(){var n=now_inl();requireLazy(["__bigPipe"],function(bigPipe){bigPipe.beforePageletArrive("first_response",n);})})();</script>
<script nonce="">requireLazy(["__bigPipe"],(function(bigPipe){bigPipe.onPageletArrive({displayResources:["6XWCS9s","XGDA5to","T/eaVKH","27iTcKo","SJt9b58","WW8fqVn","00Aws6K","vi/i3HE","foxoXrn","i4ulAqS","Yo2UzOh","P/mr5VE"],id:"first_response",phase:0,last_in_phase:true,tti_phase:0,all_phases:[63],hsrp:{hblp:{consistency:{rev:1005260860}}},allResources:["WW8fqVn","1Rv/+Xz","TDbeFtl","7xieS14","ZjF9HpG","SJt9b58","VJBByUf","i4ulAqS","00Aws6K","foxoXrn","h3A96RM","6XWCS9s","XGDA5to","T/eaVKH","27iTcKo","vi/i3HE","Yo2UzOh","DArYdIE","P/mr5VE","CGkH4FY","VYX+Uc1","dtBHfNn"]});}));</script>
<script>requireLazy(["__bigPipe"],function(bigPipe){bigPipe.setPageID("7080497951380118007-0")});CavalryLogger.setPageID("7080497951380118007-0");</script><script nonce="">(function(){var n=now_inl();requireLazy(["__bigPipe"],function(bigPipe){bigPipe.beforePageletArrive("last_response",n);})})();</script>
<script nonce="">requireLazy(["__bigPipe"],(function(bigPipe){bigPipe.onPageletArrive({displayResources:["i4ulAqS"],id:"last_response",phase:63,last_in_phase:true,the_end:true,jsmods:{define:[["TimeSliceInteractionSV",[],{on_demand_reference_counting:true,on_demand_profiling_counters:true,default_rate:1000,lite_default_rate:100,interaction_to_lite_coinflip:{ADS_INTERFACES_INTERACTION:0,ads_perf_scenario:0,ads_wait_time:0,Event:1},interaction_to_coinflip:{ADS_INTERFACES_INTERACTION:1,ads_perf_scenario:1,ads_wait_time:1,Event:100},enable_heartbeat:true,maxBlockMergeDuration:0,maxBlockMergeDistance:0,enable_banzai_stream:true,user_timing_coinflip:50,banzai_stream_coinflip:0,compression_enabled:true,ref_counting_fix:false,ref_counting_cont_fix:false,also_record_new_timeslice_format:false,force_async_request_tracing_on:false},2609],["WebDriverConfig",[],{isTestRunning:false,isJestE2ETestRun:false,auxiliaryServiceInfo:{},testPath:null,originHost:null},5332],["cr:1642797",["BanzaiBase"],{__rc:["BanzaiBase","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:1458113",[],{__rc:[null,"Aa1y2ZR3E1p-YCtufcLRz3i3pnkmhcdYVsw5idHZTWr7Q7Zc3ua1qJusVHRLBM8ToXkgpZvzOM3X7huKXbYOeQXJ89Nh8RY"]},-1],["cr:1039",[],{__rc:[null,"Aa1EErCpdRX-V7Y3hniGUM3GAwHpHb3GsqnqbOOysY7Lwa0CtOYdLGogcKmpdIwtGzy4eA1IELM"]},-1],["cr:1041",[],{__rc:[null,"Aa1EErCpdRX-V7Y3hniGUM3GAwHpHb3GsqnqbOOysY7Lwa0CtOYdLGogcKmpdIwtGzy4eA1IELM"]},-1],["cr:1048",[],{__rc:[null,"Aa1EErCpdRX-V7Y3hniGUM3GAwHpHb3GsqnqbOOysY7Lwa0CtOYdLGogcKmpdIwtGzy4eA1IELM"]},-1],["cr:917439",["PageTransitionsBlue"],{__rc:["PageTransitionsBlue","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:1108857",[],{__rc:[null,"Aa0TB90gVc6BDqkns1HNK-yI_gLhmmGxc0AT5vKIWs2szLXbHebX6mAUJehkhK6ie1cjLXo_xOdjX4aIlw"]},-1],["cr:1294158",["React.classic"],{__rc:["React.classic","Aa2V-iiYslqxNVzKRJeocz4f56uEBjfps8k-MmkKJ6kHYxvcAkfW7pqAcVEbicD3ZEzN9qlbfB7sp989xH5K0Nu51bTw"]},-1],["cr:1294246",["ReactDOM.classic"],{__rc:["ReactDOM.classic","Aa2V-iiYslqxNVzKRJeocz4f56uEBjfps8k-MmkKJ6kHYxvcAkfW7pqAcVEbicD3ZEzN9qlbfB7sp989xH5K0Nu51bTw"]},-1],["cr:1069930",[],{__rc:[null,"Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:1083116",["XAsyncRequest"],{__rc:["XAsyncRequest","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:1083117",[],{__rc:[null,"Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:2682",["warningBlueish"],{__rc:["warningBlueish","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:11202",[],{__rc:[null,"Aa0TB90gVc6BDqkns1HNK-yI_gLhmmGxc0AT5vKIWs2szLXbHebX6mAUJehkhK6ie1cjLXo_xOdjX4aIlw"]},-1],["cr:971473",["LayerHideOnTransition"],{__rc:["LayerHideOnTransition","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:1105154",[],{__rc:[null,"Aa0TB90gVc6BDqkns1HNK-yI_gLhmmGxc0AT5vKIWs2szLXbHebX6mAUJehkhK6ie1cjLXo_xOdjX4aIlw"]},-1],["BanzaiConfig",[],{MAX_SIZE:10000,MAX_WAIT:150000,MIN_WAIT:null,RESTORE_WAIT:150000,blacklist:["time_spent"],disabled:false,gks:{boosted_pagelikes:true,mercury_send_error_logging:true,platform_oauth_client_events:true,graphexplorer:true,sticker_search_ranking:true},known_routes:["artillery_javascript_actions","artillery_javascript_trace","artillery_logger_data","logger","falco","gk2_exposure","js_error_logging","loom_trace","marauder","perfx_custom_logger_endpoint","qex","require_cond_exposure_logging","sri_logger_data"],should_drop_unknown_routes:true,should_log_unknown_routes:false},7],["PageTransitionsConfig",[],{reloadOnBootloadError:true},1067],["cr:692209",["cancelIdleCallbackBlue"],{__rc:["cancelIdleCallbackBlue","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:1292365",["React-prod.classic"],{__rc:["React-prod.classic","Aa0TB90gVc6BDqkns1HNK-yI_gLhmmGxc0AT5vKIWs2szLXbHebX6mAUJehkhK6ie1cjLXo_xOdjX4aIlw"]},-1],["cr:1344485",["ReactDOM.classic.prod-or-profiling"],{__rc:["ReactDOM.classic.prod-or-profiling","Aa0TB90gVc6BDqkns1HNK-yI_gLhmmGxc0AT5vKIWs2szLXbHebX6mAUJehkhK6ie1cjLXo_xOdjX4aIlw"]},-1],["cr:2683",["warningBlue"],{__rc:["warningBlue","Aa2C2Hs5ba7NaDXhiBRuph_8SSKyn7r8EWk3g-XhRA9rC8T_M--nqbOphdQft8MnUgmsSkJyAKdDDXT1v5QxlqjkuFkS"]},-1],["CoreWarningGK",[],{forceWarning:false},725],["cr:1344486",["ReactDOM.classic.prod"],{__rc:["ReactDOM.classic.prod","Aa1-83oRBeweauTCVHgWLCkKKjMudY-dPqAokQk-ITHoXSQ956C48GTyXOSa23m_iyzWSeNrFjXRSrPGtJB6bxAMh7plFQNUbQ"]},-1],["cr:983844",[],{__rc:[null,"Aa0TB90gVc6BDqkns1HNK-yI_gLhmmGxc0AT5vKIWs2szLXbHebX6mAUJehkhK6ie1cjLXo_xOdjX4aIlw"]},-1],["cr:1344487",["ReactDOM-prod.classic"],{__rc:["ReactDOM-prod.classic","Aa3-YO8hao1Sd6_T64GdSNKM5jN30MeqsXQwgJksshL3LpQECqU_NvBeTP8mvXWLjaa-3Qy96hz9ngO7ubhM0cma82owTvmpOlcp7q83"]},-1],["cr:1353359",["EventListenerImplForBlue"],{__rc:["EventListenerImplForBlue","Aa318LRjsB_wxKi7LHnHFygHVSHj9xFX1x4Z_jAI0Hu_kytEsy1rk2OtzRxJRA9GssuUo1mi-d45vkGBTxJNZ74kY3Wp1HhImA"]},-1],["KillabyteProfilerConfig",[],{htmlProfilerModule:null,profilerModule:null,depTypes:{BL:"bl",NON_BL:"non-bl"}},1145],["QuicklingConfig",[],{version:"1005260860;0;",sessionLength:30,inactivePageRegex:"^/(fr/u\\.php|ads/|advertising|ac\\.php|ae\\.php|a\\.php|ajax/emu/(end|f|h)\\.php|badges/|comments\\.php|connect/uiserver\\.php|editalbum\\.php.+add=1|ext/|feeds/|help([/?]|$)|identity_switch\\.php|isconnectivityahumanright/|intern/|login\\.php|logout\\.php|sitetour/homepage_tour\\.php|sorry\\.php|syndication\\.php|webmessenger|/plugins/subscribe|lookback|brandpermissions|gameday|pxlcld|comet|worldcup/map|livemap|work/reseller|([^/]+/)?dialog|legal|.+\\.pdf$|.+/settings/)",badRequestKeys:["nonce","access_token","oauth_token","xs","checkpoint_data","code"],logRefreshOverhead:false},60],["TrackingConfig",[],{domain:"https://pixel.facebook.com"},325],["WebDevicePerfInfoData",[],{needsFullUpdate:true,needsPartialUpdate:false,shouldLogResourcePerf:false},3977],["WebStorageMonsterLoggingURI",[],{uri:"/ajax/webstorage/process_keys/?state=1"},3032],["BrowserPaymentHandlerConfig",[],{enabled:false},3904],["TimeSpentConfig",[],{"0_delay":0,"0_timeout":8,delay:1000,timeout:64},142],["cr:1351741",["CometEventListener"],{__rc:["CometEventListener","Aa1h8POK773YAx2kYDKRwbTFZLpYJvTOHjbBfhTFZhewA4P2re4PFzYKpNhOu46SuiOa8r5M-JIo4ErR2S6mEbRLJ5bc5l7LCCcMALmp2iCbFwvH9PXp"]},-1],["cr:1634616",["UserActivityBlue"],{__rc:["UserActivityBlue","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:844180",["TimeSpentImmediateActiveSecondsLoggerBlue"],{__rc:["TimeSpentImmediateActiveSecondsLoggerBlue","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["cr:1187159",["BlueCompatBroker"],{__rc:["BlueCompatBroker","Aa2j7LleGudqYDBnUbdsEdDv5CH6o3vjTrlKxx6VuGd_g2K3jSLeSe7qQb1JSu0Yypwcbh_EkWwMqMX85Su5wzFGvxY"]},-1],["ImmediateActiveSecondsConfig",[],{sampling_rate:0},423]],require:[["BDClientSignalCollectionTrigger","startSignalCollection",[],[{sc:"{\"t\":1637128278,\"c\":[[30000,838801],[30001,838801],[30002,838801],[30003,838801],[30004,838801],[30005,838801],[30006,573585],[30007,838801],[30008,838801],[30012,838801],[30013,838801],[30015,806033],[30018,806033],[30040,806033],[30093,806033],[30094,806033],[30095,806033],[30101,541591],[30102,541591],[30103,541591],[30104,541591],[30106,806039],[30107,806039],[38000,541427],[38001,806643]]}",fds:60,fda:60,i:60,sbs:1,dbs:100,bbs:100,hbi:60,rt:262144,hbcbc:2,hbvbc:0,hbbi:30,sid:-1,hbv:"4034802853076327353"}]],["CavalryLoggerImpl","startInstrumentation",[],[]],["NavigationMetrics","setPage",[],[{page:"XIndexReduxController",page_type:"normal",page_uri:"https://www.facebook.com/",serverLID:"7080497951380118007-0"}]],["FalcoLoggerTransports","attach",[],[]],["Chromedome","start",[],[{}]],["DimensionTracking"],["ClickRefLogger"],["DetectBrokenProxyCache","run",[],[0,"c_user"]],["NavigationClickPointHandler"],["ServiceWorkerURLCleaner","removeRedirectID",[],[]],["WebDevicePerfInfoLogging","doLog",[],[]],["WebStorageMonster","schedule",[],[]],["Artillery","disable",[],[]],["ScriptPathLogger","startLogging",[],[]],["TimeSpentBitArrayLogger","init",[],[]],["CookieCore","setWithoutChecksIfFirstPartyContext",[],["_js_datr","X_tCYqdwBYfTiQFSplpIVlN3",63072000000,"/",true]],["RequireDeferredReference","unblock",[],[["VisualCompletionGating"],"sd"]],["RequireDeferredReference","unblock",[],[["VisualCompletionGating"],"css"]]]},hsrp:{hsdp:{clpData:{"1743095":{r:1,s:1},"1871697":{r:1,s:1},"1829319":{r:1},"1829320":{r:1},"1843988":{r:1}},gkxData:{"1652843":{result:false,hash:"AT6uh9NWRY4QEQoYCCc"}},qexData:{"661":{r:null}}},hblp:{consistency:{rev:1005260860},rsrcMap:{CBQ4zUl:{type:"js",src:"https://static.xx.fbcdn.net/rsrc.php/v3/yX/r/xOJs33xJ5Fd.js?_nc_x=Ij3Wp8lg5Kz"},FEt5GzN:{type:"js",src:"https://static.xx.fbcdn.net/rsrc.php/v3/yn/r/KWY7Edb5_DT.js?_nc_x=Ij3Wp8lg5Kz"},RSfm84C:{type:"js",src:"https://static.xx.fbcdn.net/rsrc.php/v3iX3c4/yG/l/en_GB/3ni-w8nVeg8.js?_nc_x=Ij3Wp8lg5Kz"},XVtAULI:{type:"js",src:"https://static.xx.fbcdn.net/rsrc.php/v3/y9/r/ugD21mPGNBo.js?_nc_x=Ij3Wp8lg5Kz"}},compMap:{TransportSelectingClientSingleton:{r:["KnHLe0g","i4ulAqS","YxYiZwp"],rds:{m:["ContextualConfig","BladeRunnerClient","DGWRequestStreamClient","MqttLongPollingRunner","BanzaiScuba_DEPRECATED"],r:["2CbDRJL","flND0HS","5CEHaQA","SJt9b58","00Aws6K","VYX+Uc1","foxoXrn","xO06VLK"]},be:1},RequestStreamCommonRequestStreamCommonTypes:{r:["KnHLe0g"],be:1}}}},allResources:["i4ulAqS","CBQ4zUl","2CbDRJL","FEt5GzN","RSfm84C","xO06VLK","XVtAULI","45g2zGz","SJt9b58","foxoXrn","WW8fqVn","00Aws6K","wBnHkAZ","7xieS14","h3A96RM","TDbeFtl","ZjF9HpG"],onload:["CavalryLogger.getInstance(\"7080497951380118007-0\").setTTIEvent(\"t_domcontent\");"],onafterload:["CavalryLogger.getInstance(\"7080497951380118007-0\").collectBrowserTiming(window)","window.CavalryLogger&&CavalryLogger.getInstance().setTimeStamp(\"t_paint\");","if (window.ExitTime){CavalryLogger.getInstance(\"7080497951380118007-0\").setValue(\"t_exit\", window.ExitTime);};"]});}));</script></body></html>
