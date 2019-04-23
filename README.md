# dsc_extractor

Extractor dyld shared cache armxx.

# Compile

```sh
clang++ dyld/launch-cache/dsc_extractor.cpp dyld/launch-cache/dsc_iterator.cpp -o dsc_extractor
```

# Usage

```sh
./dsc_extractor dyld_shared_cache_arm64 arm64
0/1005
1/1005
2/1005
3/1005
....
1001/1005
1002/1005
1003/1005
1004/1005
dyld_shared_cache_extract_dylibs_progress() => 0
```
<details>
<summary>tree arm64</summary>
<pre><code>.
arm64
├── System
│   └── Library
│       ├── AccessibilityBundles
│       │   ├── AXSpeechImplementation.bundle
│       │   │   └── AXSpeechImplementation
│       │   ├── AccessibilitySettingsLoader.bundle
│       │   │   └── AccessibilitySettingsLoader
│       │   ├── AccountsUI.axbundle
│       │   │   └── AccountsUI
│       │   ├── AddressBookUIFramework.axbundle
│       │   │   └── AddressBookUIFramework
│       │   ├── CameraKit.axbundle
│       │   │   └── CameraKit
│       │   ├── CameraUI.axbundle
│       │   │   └── CameraUI
│       │   ├── HearingAidUIServer.axuiservice
│       │   │   └── HearingAidUIServer
│       │   ├── MapKitFramework.axbundle
│       │   │   └── MapKitFramework
│       │   ├── MediaPlayerFramework.axbundle
│       │   │   └── MediaPlayerFramework
│       │   ├── MediaPlayerUIFramework.axbundle
│       │   │   └── MediaPlayerUIFramework
│       │   ├── MessageUIFramework.axbundle
│       │   │   └── MessageUIFramework
│       │   ├── PassKitFramework.axbundle
│       │   │   └── PassKitFramework
│       │   ├── PhotoLibraryFramework.axbundle
│       │   │   └── PhotoLibraryFramework
│       │   ├── PhotoLibraryServices.axbundle
│       │   │   └── PhotoLibraryServices
│       │   ├── PhotosFramework.axbundle
│       │   │   └── PhotosFramework
│       │   ├── PhotosUIFramework.axbundle
│       │   │   └── PhotosUIFramework
│       │   ├── QuickLook.axbundle
│       │   │   └── QuickLook
│       │   ├── QuickSpeak.bundle
│       │   │   └── QuickSpeak
│       │   ├── RemoteUIFramework.axbundle
│       │   │   └── RemoteUIFramework
│       │   ├── SocialFramework.axbundle
│       │   │   └── SocialFramework
│       │   ├── StoreKitFramework.axbundle
│       │   │   └── StoreKitFramework
│       │   ├── StoreKitUI.axbundle
│       │   │   └── StoreKitUI
│       │   ├── UIKit.axbundle
│       │   │   └── UIKit
│       │   ├── VoiceMemosFramework.axbundle
│       │   │   └── VoiceMemosFramework
│       │   ├── WebCore.axbundle
│       │   │   └── WebCore
│       │   ├── WebKit.axbundle
│       │   │   └── WebKit
│       │   ├── WebKitLegacy.axbundle
│       │   │   └── WebKitLegacy
│       │   ├── WebProcess.axbundle
│       │   │   └── WebProcess
│       │   ├── WebProcessLoader.axbundle
│       │   │   └── WebProcessLoader
│       │   └── iTunesStoreFramework.axbundle
│       │       └── iTunesStoreFramework
│       ├── BulletinBoardPlugins
│       │   ├── CMASBBPlugin.bundle
│       │   │   └── CMASBBPlugin
│       │   ├── MPDataProvider.bundle
│       │   │   └── MPDataProvider
│       │   ├── PhotoLibraryDataProvider.bundle
│       │   │   └── PhotoLibraryDataProvider
│       │   ├── SMSBBPlugin.bundle
│       │   │   └── SMSBBPlugin
│       │   ├── SocialBulletinBoardProvider.bundle
│       │   │   └── SocialBulletinBoardProvider
│       │   └── WeatherNotifications.bundle
│       │       └── WeatherNotifications
│       ├── Caches
│       │   ├── com.apple.xpc
│       │   │   └── sdk.dylib
│       │   └── com.apple.xpcd
│       │       └── xpcd_cache.dylib
│       ├── CoreServices
│       │   ├── Encodings
│       │   │   ├── libArabicConverter.dylib
│       │   │   ├── libCyrillicConverter.dylib
│       │   │   ├── libGreekConverter.dylib
│       │   │   ├── libHebrewConverter.dylib
│       │   │   ├── libJapaneseConverter.dylib
│       │   │   ├── libKoreanConverter.dylib
│       │   │   ├── libLatin2Converter.dylib
│       │   │   ├── libLatin5Converter.dylib
│       │   │   ├── libLatinSuppConverter.dylib
│       │   │   ├── libSimplifiedChineseConverter.dylib
│       │   │   ├── libSymbolConverter.dylib
│       │   │   ├── libThaiConverter.dylib
│       │   │   ├── libTraditionalChineseConverter.dylib
│       │   │   └── libVietnameseConverter.dylib
│       │   └── RawCamera.bundle
│       │       └── RawCamera
│       ├── DataClassMigrators
│       │   ├── DAAccount.migrator
│       │   │   └── DAAccount
│       │   ├── DAAccountLegacy.migrator
│       │   │   └── DAAccountLegacy
│       │   ├── FaceTimeMigrator.migrator
│       │   │   └── FaceTimeMigrator
│       │   └── MessagesDataMigrator.migrator
│       │       └── MessagesDataMigrator
│       ├── Extensions
│       │   ├── AGXGLDriver.bundle
│       │   │   └── AGXGLDriver
│       │   ├── AppleHDQGasGaugeControl.kext
│       │   │   └── PlugIns
│       │   │       └── AppleHDQGasGaugeHID.plugin
│       │   │           └── AppleHDQGasGaugeHID
│       │   └── IOHIDFamily.kext
│       │       └── PlugIns
│       │           └── IOHIDLib.plugin
│       │               └── IOHIDLib
│       ├── Frameworks
│       │   ├── AVFoundation.framework
│       │   │   ├── AVFoundation
│       │   │   └── libAVFAudio.dylib
│       │   ├── AVKit.framework
│       │   │   └── AVKit
│       │   ├── Accelerate.framework
│       │   │   ├── Accelerate
│       │   │   └── Frameworks
│       │   │       ├── vImage.framework
│       │   │       │   ├── Libraries
│       │   │       │   │   └── libCGInterfaces.dylib
│       │   │       │   └── vImage
│       │   │       └── vecLib.framework
│       │   │           ├── libBLAS.dylib
│       │   │           ├── libLAPACK.dylib
│       │   │           ├── libLinearAlgebra.dylib
│       │   │           ├── libSparseBLAS.dylib
│       │   │           ├── libvDSP.dylib
│       │   │           ├── libvMisc.dylib
│       │   │           └── vecLib
│       │   ├── Accounts.framework
│       │   │   └── Accounts
│       │   ├── AdSupport.framework
│       │   │   └── AdSupport
│       │   ├── AddressBook.framework
│       │   │   └── AddressBook
│       │   ├── AddressBookUI.framework
│       │   │   └── AddressBookUI
│       │   ├── AssetsLibrary.framework
│       │   │   └── AssetsLibrary
│       │   ├── AudioToolbox.framework
│       │   │   ├── AudioCodecs
│       │   │   ├── AudioToolbox
│       │   │   ├── libAudioDSP.dylib
│       │   │   └── libVibeSynthEngine.dylib
│       │   ├── CFNetwork.framework
│       │   │   └── CFNetwork
│       │   ├── CloudKit.framework
│       │   │   └── CloudKit
│       │   ├── Contacts.framework
│       │   │   └── Contacts
│       │   ├── ContactsUI.framework
│       │   │   └── ContactsUI
│       │   ├── CoreAudio.framework
│       │   │   └── CoreAudio
│       │   ├── CoreAudioKit.framework
│       │   │   └── CoreAudioKit
│       │   ├── CoreBluetooth.framework
│       │   │   └── CoreBluetooth
│       │   ├── CoreData.framework
│       │   │   └── CoreData
│       │   ├── CoreFoundation.framework
│       │   │   └── CoreFoundation
│       │   ├── CoreGraphics.framework
│       │   │   ├── CoreGraphics
│       │   │   └── Resources
│       │   │       ├── libCGCorePDF.A.dylib
│       │   │       ├── libCGCorePDF.dylib
│       │   │       ├── libCGVolute.A.dylib
│       │   │       ├── libCGVolute.dylib
│       │   │       ├── libCGXType.A.dylib
│       │   │       ├── libCGXType.dylib
│       │   │       ├── libCMaps.A.dylib
│       │   │       ├── libCMaps.dylib
│       │   │       ├── libFontStreams.A.dylib
│       │   │       ├── libFontStreams.dylib
│       │   │       ├── libJBIG2.A.dylib
│       │   │       ├── libJBIG2.dylib
│       │   │       ├── libPDFRIP.A.dylib
│       │   │       ├── libPDFRIP.dylib
│       │   │       ├── libRIP.A.dylib
│       │   │       └── libRIP.dylib
│       │   ├── CoreImage.framework
│       │   │   └── CoreImage
│       │   ├── CoreLocation.framework
│       │   │   └── CoreLocation
│       │   ├── CoreMIDI.framework
│       │   │   └── CoreMIDI
│       │   ├── CoreMedia.framework
│       │   │   └── CoreMedia
│       │   ├── CoreMotion.framework
│       │   │   └── CoreMotion
│       │   ├── CoreSpotlight.framework
│       │   │   └── CoreSpotlight
│       │   ├── CoreTelephony.framework
│       │   │   └── CoreTelephony
│       │   ├── CoreText.framework
│       │   │   └── CoreText
│       │   ├── CoreVideo.framework
│       │   │   └── CoreVideo
│       │   ├── EventKit.framework
│       │   │   └── EventKit
│       │   ├── EventKitUI.framework
│       │   │   └── EventKitUI
│       │   ├── ExternalAccessory.framework
│       │   │   └── ExternalAccessory
│       │   ├── Foundation.framework
│       │   │   └── Foundation
│       │   ├── GLKit.framework
│       │   │   └── GLKit
│       │   ├── GSS.framework
│       │   │   └── GSS
│       │   ├── GameController.framework
│       │   │   └── GameController
│       │   ├── GameKit.framework
│       │   │   └── GameKit
│       │   ├── GameplayKit.framework
│       │   │   └── GameplayKit
│       │   ├── HealthKit.framework
│       │   │   └── HealthKit
│       │   ├── HomeKit.framework
│       │   │   └── HomeKit
│       │   ├── IOKit.framework
│       │   │   ├── IOKit
│       │   │   └── Versions
│       │   │       └── A
│       │   │           └── IOKit
│       │   ├── ImageIO.framework
│       │   │   └── ImageIO
│       │   ├── JavaScriptCore.framework
│       │   │   ├── JavaScriptCore
│       │   │   └── Libraries
│       │   │       └── libllvmForJSC.dylib
│       │   ├── LocalAuthentication.framework
│       │   │   ├── LocalAuthentication
│       │   │   └── Support
│       │   │       └── SharedUtils.framework
│       │   │           └── SharedUtils
│       │   ├── MapKit.framework
│       │   │   └── MapKit
│       │   ├── MediaAccessibility.framework
│       │   │   └── MediaAccessibility
│       │   ├── MediaPlayer.framework
│       │   │   └── MediaPlayer
│       │   ├── MediaToolbox.framework
│       │   │   └── MediaToolbox
│       │   ├── MessageUI.framework
│       │   │   └── MessageUI
│       │   ├── Metal.framework
│       │   │   └── Metal
│       │   ├── MetalKit.framework
│       │   │   └── MetalKit
│       │   ├── MetalPerformanceShaders.framework
│       │   │   └── MetalPerformanceShaders
│       │   ├── MobileCoreServices.framework
│       │   │   └── MobileCoreServices
│       │   ├── ModelIO.framework
│       │   │   └── ModelIO
│       │   ├── MultipeerConnectivity.framework
│       │   │   └── MultipeerConnectivity
│       │   ├── NetworkExtension.framework
│       │   │   └── NetworkExtension
│       │   ├── NewsstandKit.framework
│       │   │   └── NewsstandKit
│       │   ├── NotificationCenter.framework
│       │   │   └── NotificationCenter
│       │   ├── OpenAL.framework
│       │   │   └── OpenAL
│       │   ├── OpenGLES.framework
│       │   │   ├── GLEngine.bundle
│       │   │   │   └── GLEngine
│       │   │   ├── OpenGLES
│       │   │   ├── libCLRendererStubs.dylib
│       │   │   ├── libCVMSPluginSupport.dylib
│       │   │   ├── libCoreFSCache.dylib
│       │   │   ├── libCoreVMClient.dylib
│       │   │   ├── libGFXShared.dylib
│       │   │   ├── libGLImage.dylib
│       │   │   ├── libGLProgrammability.dylib
│       │   │   ├── libGLVMPlugin.dylib
│       │   │   └── libLLVMContainer.dylib
│       │   ├── PassKit.framework
│       │   │   └── PassKit
│       │   ├── Photos.framework
│       │   │   └── Photos
│       │   ├── PhotosUI.framework
│       │   │   └── PhotosUI
│       │   ├── PushKit.framework
│       │   │   └── PushKit
│       │   ├── QuartzCore.framework
│       │   │   └── QuartzCore
│       │   ├── QuickLook.framework
│       │   │   └── QuickLook
│       │   ├── ReplayKit.framework
│       │   │   └── ReplayKit
│       │   ├── SafariServices.framework
│       │   │   └── SafariServices
│       │   ├── SceneKit.framework
│       │   │   └── SceneKit
│       │   ├── Security.framework
│       │   │   └── Security
│       │   ├── Social.framework
│       │   │   └── Social
│       │   ├── SpriteKit.framework
│       │   │   └── SpriteKit
│       │   ├── StoreKit.framework
│       │   │   └── StoreKit
│       │   ├── System.framework
│       │   │   └── System
│       │   ├── SystemConfiguration.framework
│       │   │   └── SystemConfiguration
│       │   ├── Twitter.framework
│       │   │   └── Twitter
│       │   ├── UIKit.framework
│       │   │   └── UIKit
│       │   ├── VideoToolbox.framework
│       │   │   └── VideoToolbox
│       │   ├── WatchConnectivity.framework
│       │   │   └── WatchConnectivity
│       │   ├── WatchKit.framework
│       │   │   └── WatchKit
│       │   ├── WebKit.framework
│       │   │   └── WebKit
│       │   └── iAd.framework
│       │       └── iAd
│       ├── MediaCapture
│       │   └── H6ISP.mediacapture
│       ├── Messages
│       │   └── PlugIns
│       │       ├── FaceTime.imservice
│       │       │   └── FaceTime
│       │       ├── SMS.imservice
│       │       │   └── SMS
│       │       └── iMessage.imservice
│       │           └── iMessage
│       ├── PreferenceBundles
│       │   ├── AccountSettings
│       │   │   ├── ActiveSyncSettings.bundle
│       │   │   │   └── ActiveSyncSettings
│       │   │   ├── ContactsSettings.bundle
│       │   │   │   └── ContactsSettings
│       │   │   ├── DAVSettings.bundle
│       │   │   │   └── DAVSettings
│       │   │   ├── LDAPSettings.bundle
│       │   │   │   └── LDAPSettings
│       │   │   ├── MobileCalSettings.bundle
│       │   │   │   └── MobileCalSettings
│       │   │   ├── MobileMailSettings.bundle
│       │   │   │   └── MobileMailSettings
│       │   │   └── SubscribedCalendarSettings.bundle
│       │   │       └── SubscribedCalendarSettings
│       │   ├── AirPortSettings.bundle
│       │   │   └── AirPortSettings
│       │   ├── BluetoothSettings.bundle
│       │   │   └── BluetoothSettings
│       │   ├── CarrierSettings.bundle
│       │   │   └── CarrierSettings
│       │   ├── EDGESettings.bundle
│       │   │   └── EDGESettings
│       │   ├── KeyboardSettings.bundle
│       │   │   └── KeyboardSettings
│       │   ├── ManagedConfigurationUI.bundle
│       │   │   └── ManagedConfigurationUI
│       │   ├── MobilePhoneSettings.bundle
│       │   │   └── MobilePhoneSettings
│       │   ├── MobileSafariSettings.bundle
│       │   │   └── MobileSafariSettings
│       │   ├── MobileSlideShowSettings.bundle
│       │   │   └── MobileSlideShowSettings
│       │   ├── MobileStoreSettings.bundle
│       │   │   └── MobileStoreSettings
│       │   ├── ScheduleSettings.bundle
│       │   │   └── ScheduleSettings
│       │   ├── VPNPreferences.bundle
│       │   │   └── VPNPreferences
│       │   ├── Wallpaper.bundle
│       │   │   └── Wallpaper
│       │   └── WirelessModemSettings.bundle
│       │       └── WirelessModemSettings
│       ├── PrivateFrameworks
│       │   ├── ACTFramework.framework
│       │   │   └── ACTFramework
│       │   ├── AGXCompilerConnection.framework
│       │   │   └── AGXCompilerConnection
│       │   ├── AGXCompilerCore.framework
│       │   │   └── AGXCompilerCore
│       │   ├── AITTarget.framework
│       │   │   └── AITTarget
│       │   ├── AOSKit.framework
│       │   │   └── AOSKit
│       │   ├── AOSNotification.framework
│       │   │   └── AOSNotification
│       │   ├── APTransport.framework
│       │   │   └── APTransport
│       │   ├── ATFoundation.framework
│       │   │   └── ATFoundation
│       │   ├── AXRuntime.framework
│       │   │   └── AXRuntime
│       │   ├── Accessibility.framework
│       │   │   └── Frameworks
│       │   │       ├── AXElementInteraction.framework
│       │   │       │   └── AXElementInteraction
│       │   │       ├── AXFrontBoardUtils.framework
│       │   │       │   └── AXFrontBoardUtils
│       │   │       ├── AXHearingSupport.framework
│       │   │       │   └── AXHearingSupport
│       │   │       ├── AXMediaUtilities.framework
│       │   │       │   └── AXMediaUtilities
│       │   │       ├── AXSpringBoardServerInstance.framework
│       │   │       │   └── AXSpringBoardServerInstance
│       │   │       ├── AccessibilityUI.framework
│       │   │       │   └── AccessibilityUI
│       │   │       ├── AccessibilityUIService.framework
│       │   │       │   └── AccessibilityUIService
│       │   │       ├── AccessibilityUIUtilities.framework
│       │   │       │   └── AccessibilityUIUtilities
│       │   │       ├── SpeakThisServices.framework
│       │   │       │   └── SpeakThisServices
│       │   │       └── ZoomServices.framework
│       │   │           └── ZoomServices
│       │   ├── AccessibilityUtilities.framework
│       │   │   └── AccessibilityUtilities
│       │   ├── AccountNotification.framework
│       │   │   └── AccountNotification
│       │   ├── AccountSettings.framework
│       │   │   └── AccountSettings
│       │   ├── AccountsDaemon.framework
│       │   │   └── AccountsDaemon
│       │   ├── AccountsUI.framework
│       │   │   └── AccountsUI
│       │   ├── AggregateDictionary.framework
│       │   │   └── AggregateDictionary
│       │   ├── AggregateDictionaryHistory.framework
│       │   │   └── AggregateDictionaryHistory
│       │   ├── AirPlayForCarDisplaySim.framework
│       │   │   └── AirPlayForCarDisplaySim
│       │   ├── AirPlaySender.framework
│       │   │   └── AirPlaySender
│       │   ├── AirPlaySupport.framework
│       │   │   └── AirPlaySupport
│       │   ├── AirPortAssistant.framework
│       │   │   └── AirPortAssistant
│       │   ├── AirTraffic.framework
│       │   │   └── AirTraffic
│       │   ├── AirTrafficDevice.framework
│       │   │   └── AirTrafficDevice
│       │   ├── AnnotationKit.framework
│       │   │   └── AnnotationKit
│       │   ├── AppConduit.framework
│       │   │   └── AppConduit
│       │   ├── AppLaunchStats.framework
│       │   │   └── AppLaunchStats
│       │   ├── AppPredictionInternal.framework
│       │   │   └── AppPredictionInternal
│       │   ├── AppStoreUI.framework
│       │   │   └── AppStoreUI
│       │   ├── AppSupport.framework
│       │   │   └── AppSupport
│       │   ├── AppleAccount.framework
│       │   │   └── AppleAccount
│       │   ├── AppleAccountUI.framework
│       │   │   └── AppleAccountUI
│       │   ├── AppleBasebandManager.framework
│       │   │   └── AppleBasebandManager
│       │   ├── AppleBasebandServices.framework
│       │   │   └── AppleBasebandServices
│       │   ├── AppleFSCompression.framework
│       │   │   └── AppleFSCompression
│       │   ├── AppleIDAuthSupport.framework
│       │   │   └── AppleIDAuthSupport
│       │   ├── AppleIDSSOAuthentication.framework
│       │   │   └── AppleIDSSOAuthentication
│       │   ├── AppleJPEG.framework
│       │   │   └── AppleJPEG
│       │   ├── AppleLDAP.framework
│       │   │   └── AppleLDAP
│       │   ├── ApplePDPHelper.framework
│       │   │   └── ApplePDPHelper
│       │   ├── ApplePushService.framework
│       │   │   └── ApplePushService
│       │   ├── AppleSRP.framework
│       │   │   └── AppleSRP
│       │   ├── AppleSauce.framework
│       │   │   └── AppleSauce
│       │   ├── AppleSerialMultiplexer.framework
│       │   │   └── AppleSerialMultiplexer
│       │   ├── AskPermission.framework
│       │   │   └── AskPermission
│       │   ├── AssertionServices.framework
│       │   │   └── AssertionServices
│       │   ├── AssetCacheServices.framework
│       │   │   └── AssetCacheServices
│       │   ├── AssetsLibraryServices.framework
│       │   │   └── AssetsLibraryServices
│       │   ├── AssistantServices.framework
│       │   │   └── AssistantServices
│       │   ├── AssistantUI.framework
│       │   │   └── AssistantUI
│       │   ├── AuthKit.framework
│       │   │   └── AuthKit
│       │   ├── AuthKitUI.framework
│       │   │   └── AuthKitUI
│       │   ├── BTLEAudioController.framework
│       │   │   └── BTLEAudioController
│       │   ├── BackBoardServices.framework
│       │   │   └── BackBoardServices
│       │   ├── BackgroundTaskAgent.framework
│       │   │   └── BackgroundTaskAgent
│       │   ├── BaseBoard.framework
│       │   │   └── BaseBoard
│       │   ├── BaseBoardUI.framework
│       │   │   └── BaseBoardUI
│       │   ├── BatteryCenter.framework
│       │   │   └── BatteryCenter
│       │   ├── BiometricKit.framework
│       │   │   └── BiometricKit
│       │   ├── BiometricKitUI.framework
│       │   │   └── BiometricKitUI
│       │   ├── BluetoothManager.framework
│       │   │   └── BluetoothManager
│       │   ├── Bom.framework
│       │   │   └── Bom
│       │   ├── BookmarkDAV.framework
│       │   │   └── BookmarkDAV
│       │   ├── BridgePreferences.framework
│       │   │   └── BridgePreferences
│       │   ├── BulletinBoard.framework
│       │   │   └── BulletinBoard
│       │   ├── BulletinDistributorCompanion.framework
│       │   │   └── BulletinDistributorCompanion
│       │   ├── CPMLBestShim.framework
│       │   │   └── CPMLBestShim
│       │   ├── CacheDelete.framework
│       │   │   └── CacheDelete
│       │   ├── CalDAV.framework
│       │   │   └── CalDAV
│       │   ├── Calculate.framework
│       │   │   └── Calculate
│       │   ├── CalendarDaemon.framework
│       │   │   └── CalendarDaemon
│       │   ├── CalendarDatabase.framework
│       │   │   └── CalendarDatabase
│       │   ├── CalendarFoundation.framework
│       │   │   └── CalendarFoundation
│       │   ├── CalendarUIKit.framework
│       │   │   └── CalendarUIKit
│       │   ├── CallHistory.framework
│       │   │   └── CallHistory
│       │   ├── CameraKit.framework
│       │   │   └── CameraKit
│       │   ├── CameraUI.framework
│       │   │   └── CameraUI
│       │   ├── CaptiveNetwork.framework
│       │   │   └── CaptiveNetwork
│       │   ├── CarKit.framework
│       │   │   └── CarKit
│       │   ├── Celestial.framework
│       │   │   └── Celestial
│       │   ├── CellularPlanManager.framework
│       │   │   └── CellularPlanManager
│       │   ├── CertInfo.framework
│       │   │   └── CertInfo
│       │   ├── CertUI.framework
│       │   │   └── CertUI
│       │   ├── ChatKit.framework
│       │   │   └── ChatKit
│       │   ├── ChunkingLibrary.framework
│       │   │   └── ChunkingLibrary
│       │   ├── CloudDocs.framework
│       │   │   └── CloudDocs
│       │   ├── CloudDocsDaemon.framework
│       │   │   └── CloudDocsDaemon
│       │   ├── CloudKitDaemon.framework
│       │   │   └── CloudKitDaemon
│       │   ├── CloudPhotoLibrary.framework
│       │   │   └── CloudPhotoLibrary
│       │   ├── CloudServices.framework
│       │   │   ├── CloudServices
│       │   │   └── Frameworks
│       │   │       └── EscrowService.framework
│       │   │           └── EscrowService
│       │   ├── ColorSync.framework
│       │   │   └── ColorSync
│       │   ├── CommonAuth.framework
│       │   │   └── CommonAuth
│       │   ├── CommonUtilities.framework
│       │   │   └── CommonUtilities
│       │   ├── CommunicationsFilter.framework
│       │   │   └── CommunicationsFilter
│       │   ├── CommunicationsSetupUI.framework
│       │   │   └── CommunicationsSetupUI
│       │   ├── CompanionCamera.framework
│       │   │   └── CompanionCamera
│       │   ├── CompanionFindMy.framework
│       │   │   └── CompanionFindMy
│       │   ├── CompanionSync.framework
│       │   │   └── CompanionSync
│       │   ├── CompassUI.framework
│       │   │   └── CompassUI
│       │   ├── Conference.framework
│       │   │   └── Conference
│       │   ├── ConstantClasses.framework
│       │   │   └── ConstantClasses
│       │   ├── ContactsAutocomplete.framework
│       │   │   └── ContactsAutocomplete
│       │   ├── ContactsFoundation.framework
│       │   │   └── ContactsFoundation
│       │   ├── ContentIndex.framework
│       │   │   └── ContentIndex
│       │   ├── CoreAUC.framework
│       │   │   └── CoreAUC
│       │   ├── CoreActivity.framework
│       │   │   └── CoreActivity
│       │   ├── CoreBrightness.framework
│       │   │   └── CoreBrightness
│       │   ├── CoreCDP.framework
│       │   │   └── CoreCDP
│       │   ├── CoreCDPInternal.framework
│       │   │   └── CoreCDPInternal
│       │   ├── CoreCDPUI.framework
│       │   │   └── CoreCDPUI
│       │   ├── CoreCapture.framework
│       │   │   └── CoreCapture
│       │   ├── CoreCaptureControl.framework
│       │   │   └── CoreCaptureControl
│       │   ├── CoreCaptureDaemon.framework
│       │   │   └── CoreCaptureDaemon
│       │   ├── CoreDAV.framework
│       │   │   └── CoreDAV
│       │   ├── CoreDuet.framework
│       │   │   └── CoreDuet
│       │   ├── CoreDuetDaemonProtocol.framework
│       │   │   └── CoreDuetDaemonProtocol
│       │   ├── CoreDuetDataModel.framework
│       │   │   └── CoreDuetDataModel
│       │   ├── CoreDuetDebugLogging.framework
│       │   │   └── CoreDuetDebugLogging
│       │   ├── CoreDuetStatistics.framework
│       │   │   └── CoreDuetStatistics
│       │   ├── CoreFollowUp.framework
│       │   │   └── CoreFollowUp
│       │   ├── CoreFollowUpUI.framework
│       │   │   └── CoreFollowUpUI
│       │   ├── CoreHAP.framework
│       │   │   └── CoreHAP
│       │   ├── CoreHandwriting.framework
│       │   │   └── CoreHandwriting
│       │   ├── CoreIndoor.framework
│       │   │   └── CoreIndoor
│       │   ├── CoreMediaStream.framework
│       │   │   └── CoreMediaStream
│       │   ├── CoreNLP.framework
│       │   │   └── CoreNLP
│       │   ├── CoreOptimization.framework
│       │   │   └── CoreOptimization
│       │   ├── CorePDF.framework
│       │   │   └── CorePDF
│       │   ├── CorePrediction.framework
│       │   │   └── CorePrediction
│       │   ├── CoreRC.framework
│       │   │   └── CoreRC
│       │   ├── CoreRecents.framework
│       │   │   └── CoreRecents
│       │   ├── CoreRecognition.framework
│       │   │   └── CoreRecognition
│       │   ├── CoreRoutine.framework
│       │   │   └── CoreRoutine
│       │   ├── CoreSDB.framework
│       │   │   └── CoreSDB
│       │   ├── CoreServicesInternal.framework
│       │   │   └── CoreServicesInternal
│       │   ├── CoreSuggestions.framework
│       │   │   └── CoreSuggestions
│       │   ├── CoreSuggestionsInternals.framework
│       │   │   └── CoreSuggestionsInternals
│       │   ├── CoreSymbolication.framework
│       │   │   └── CoreSymbolication
│       │   ├── CoreTelephonyBypass.framework
│       │   │   └── CoreTelephonyBypass
│       │   ├── CoreThemeDefinition.framework
│       │   │   └── CoreThemeDefinition
│       │   ├── CoreTime.framework
│       │   │   └── CoreTime
│       │   ├── CoreUI.framework
│       │   │   └── CoreUI
│       │   ├── CoreUtils.framework
│       │   │   └── CoreUtils
│       │   ├── CrashReporterSupport.framework
│       │   │   └── CrashReporterSupport
│       │   ├── CryptoTokenKit.framework
│       │   │   └── CryptoTokenKit
│       │   ├── DAAPKit.framework
│       │   │   └── DAAPKit
│       │   ├── DCIMServices.framework
│       │   │   └── DCIMServices
│       │   ├── DataAccess.framework
│       │   │   ├── DataAccess
│       │   │   └── Frameworks
│       │   │       ├── DABookmarkDAV.framework
│       │   │       │   ├── DABookmarkDAV
│       │   │       │   └── DADaemonBookmarkDAV.bundle
│       │   │       │       └── DADaemonBookmarkDAV
│       │   │       ├── DACalDAV.framework
│       │   │       │   ├── DACalDAV
│       │   │       │   └── DADaemonCalDAV.bundle
│       │   │       │       └── DADaemonCalDAV
│       │   │       ├── DACardDAV.framework
│       │   │       │   ├── DACardDAV
│       │   │       │   └── DADaemonCardDAV.bundle
│       │   │       │       └── DADaemonCardDAV
│       │   │       ├── DACoreDAVGlue.framework
│       │   │       │   └── DACoreDAVGlue
│       │   │       ├── DADaemonSupport.framework
│       │   │       │   └── DADaemonSupport
│       │   │       ├── DAEAS.framework
│       │   │       │   ├── DADaemonEAS.bundle
│       │   │       │   │   └── DADaemonEAS
│       │   │       │   └── DAEAS
│       │   │       ├── DAIMAPNotes.framework
│       │   │       │   ├── DADaemonIMAPNotes.bundle
│       │   │       │   │   └── DADaemonIMAPNotes
│       │   │       │   └── DAIMAPNotes
│       │   │       ├── DALDAP.framework
│       │   │       │   ├── DADaemonLDAP.bundle
│       │   │       │   │   └── DADaemonLDAP
│       │   │       │   └── DALDAP
│       │   │       └── DASubCal.framework
│       │   │           ├── DADaemonSubCal.bundle
│       │   │           │   └── DADaemonSubCal
│       │   │           └── DASubCal
│       │   ├── DataAccessExpress.framework
│       │   │   └── DataAccessExpress
│       │   ├── DataAccessUI.framework
│       │   │   └── DataAccessUI
│       │   ├── DataDetectorsCore.framework
│       │   │   ├── DataDetectorsCore
│       │   │   └── PlugIns
│       │   │       └── PhoneNumbers.plugin
│       │   │           └── PhoneNumbers
│       │   ├── DataDetectorsNaturalLanguage.framework
│       │   │   └── DataDetectorsNaturalLanguage
│       │   ├── DataDetectorsUI.framework
│       │   │   └── DataDetectorsUI
│       │   ├── DataMigration.framework
│       │   │   └── DataMigration
│       │   ├── DeviceOMatic.framework
│       │   │   └── DeviceOMatic
│       │   ├── DeviceToDeviceManager.framework
│       │   │   └── DeviceToDeviceManager
│       │   ├── DiagnosticExtensions.framework
│       │   │   └── DiagnosticExtensions
│       │   ├── DiagnosticLogCollection.framework
│       │   │   └── DiagnosticLogCollection
│       │   ├── DictionaryServices.framework
│       │   │   └── DictionaryServices
│       │   ├── DiskSpaceDiagnostics.framework
│       │   │   └── DiskSpaceDiagnostics
│       │   ├── Duet.framework
│       │   │   └── Duet
│       │   ├── DuetExpertCenter.framework
│       │   │   └── DuetExpertCenter
│       │   ├── DuetPLLConfigLogger.framework
│       │   │   └── DuetPLLConfigLogger
│       │   ├── DuetRecommendation.framework
│       │   │   └── DuetRecommendation
│       │   ├── EAFirmwareUpdater.framework
│       │   │   └── EAFirmwareUpdater
│       │   ├── EAP8021X.framework
│       │   │   └── EAP8021X
│       │   ├── ETPeople.framework
│       │   │   └── ETPeople
│       │   ├── EasyConfig.framework
│       │   │   └── EasyConfig
│       │   ├── FMCore.framework
│       │   │   └── FMCore
│       │   ├── FMCoreLite.framework
│       │   │   └── FMCoreLite
│       │   ├── FMCoreUI.framework
│       │   │   └── FMCoreUI
│       │   ├── FMF.framework
│       │   │   └── FMF
│       │   ├── FMFUI.framework
│       │   │   └── FMFUI
│       │   ├── FTAWD.framework
│       │   │   └── FTAWD
│       │   ├── FTClientServices.framework
│       │   │   └── FTClientServices
│       │   ├── FTServices.framework
│       │   │   └── FTServices
│       │   ├── FaceCore.framework
│       │   │   └── FaceCore
│       │   ├── FamilyCircle.framework
│       │   │   └── FamilyCircle
│       │   ├── FamilyNotification.framework
│       │   │   └── FamilyNotification
│       │   ├── FileProvider.framework
│       │   │   └── FileProvider
│       │   ├── FindMyDevice.framework
│       │   │   └── FindMyDevice
│       │   ├── FindMyDeviceUI.framework
│       │   │   └── FindMyDeviceUI
│       │   ├── FitnessUI.framework
│       │   │   └── FitnessUI
│       │   ├── FlightUtilities.framework
│       │   │   └── FlightUtilities
│       │   ├── FontServices.framework
│       │   │   ├── FontServices
│       │   │   ├── libFontParser.dylib
│       │   │   ├── libGSFontCache.dylib
│       │   │   ├── libTrueTypeScaler.dylib
│       │   │   └── libType1Scaler.dylib
│       │   ├── FoundationODR.framework
│       │   │   └── FoundationODR
│       │   ├── FrontBoard.framework
│       │   │   └── FrontBoard
│       │   ├── FrontBoardServices.framework
│       │   │   └── FrontBoardServices
│       │   ├── FuseUI.framework
│       │   │   └── FuseUI
│       │   ├── Futhark.framework
│       │   │   └── Futhark
│       │   ├── GPUCompiler.framework
│       │   │   ├── libComposeFilters.dylib
│       │   │   ├── libmetal_timestamp.dylib
│       │   │   └── libsrc2module.dylib
│       │   ├── GPUSupport.framework
│       │   │   ├── libGPUSupport.dylib
│       │   │   └── libGPUSupportMercury.dylib
│       │   ├── GameCenter.framework
│       │   │   └── GameCenter
│       │   ├── GameCenterFoundation.framework
│       │   │   └── GameCenterFoundation
│       │   ├── GameCenterPrivateUI.framework
│       │   │   └── GameCenterPrivateUI
│       │   ├── GameCenterUI.framework
│       │   │   └── GameCenterUI
│       │   ├── GameKitServices.framework
│       │   │   ├── Frameworks
│       │   │   │   ├── AVConference.framework
│       │   │   │   │   └── AVConference
│       │   │   │   ├── GKSPerformance.framework
│       │   │   │   │   └── GKSPerformance
│       │   │   │   ├── ICE.framework
│       │   │   │   │   └── ICE
│       │   │   │   ├── LegacyHandle.framework
│       │   │   │   │   └── LegacyHandle
│       │   │   │   ├── SimpleKeyExchange.framework
│       │   │   │   │   └── SimpleKeyExchange
│       │   │   │   ├── ViceroyTrace.framework
│       │   │   │   │   └── ViceroyTrace
│       │   │   │   └── snatmap.framework
│       │   │   │       └── snatmap
│       │   │   └── GameKitServices
│       │   ├── GenerationalStorage.framework
│       │   │   └── GenerationalStorage
│       │   ├── GeoServices.framework
│       │   │   └── GeoServices
│       │   ├── GraphicsServices.framework
│       │   │   └── GraphicsServices
│       │   ├── H6ISPServices.framework
│       │   │   └── H6ISPServices
│       │   ├── HSAAuthentication.framework
│       │   │   └── HSAAuthentication
│       │   ├── HangTracer.framework
│       │   │   └── HangTracer
│       │   ├── HealthDaemon.framework
│       │   │   └── HealthDaemon
│       │   ├── HealthKitExtensions.framework
│       │   │   └── HealthKitExtensions
│       │   ├── HealthKitUI.framework
│       │   │   └── HealthKitUI
│       │   ├── Heimdal.framework
│       │   │   └── Heimdal
│       │   ├── HelpKit.framework
│       │   │   └── HelpKit
│       │   ├── HomeKitDaemon.framework
│       │   │   └── HomeKitDaemon
│       │   ├── HomeSharing.framework
│       │   │   └── HomeSharing
│       │   ├── IAP.framework
│       │   │   └── IAP
│       │   ├── IAPAuthentication.framework
│       │   │   └── IAPAuthentication
│       │   ├── IDS.framework
│       │   │   └── IDS
│       │   ├── IDSFoundation.framework
│       │   │   └── IDSFoundation
│       │   ├── IMAVCore.framework
│       │   │   └── IMAVCore
│       │   ├── IMCore.framework
│       │   │   └── IMCore
│       │   ├── IMDMessageServices.framework
│       │   │   └── IMDMessageServices
│       │   ├── IMDPersistence.framework
│       │   │   └── IMDPersistence
│       │   ├── IMDaemonCore.framework
│       │   │   └── IMDaemonCore
│       │   ├── IMFoundation.framework
│       │   │   └── IMFoundation
│       │   ├── IMTranscoding.framework
│       │   │   └── IMTranscoding
│       │   ├── IMTransferServices.framework
│       │   │   └── IMTransferServices
│       │   ├── IOAccelerator.framework
│       │   │   └── IOAccelerator
│       │   ├── IOCEC.framework
│       │   │   └── IOCEC
│       │   ├── IOMobileFramebuffer.framework
│       │   │   └── IOMobileFramebuffer
│       │   ├── IOSurface.framework
│       │   │   └── IOSurface
│       │   ├── IOSurfaceAccelerator.framework
│       │   │   └── IOSurfaceAccelerator
│       │   ├── IPTelephony.framework
│       │   │   └── Support
│       │   │       └── libIPTelephony.dylib
│       │   ├── ITMLKit.framework
│       │   │   └── ITMLKit
│       │   ├── ImageCapture.framework
│       │   │   └── ImageCapture
│       │   ├── IncomingCallFilter.framework
│       │   │   └── IncomingCallFilter
│       │   ├── InternationalTextSearch.framework
│       │   │   └── InternationalTextSearch
│       │   ├── IntlPreferences.framework
│       │   │   └── IntlPreferences
│       │   ├── JavaScriptCore.framework
│       │   │   └── JavaScriptCore
│       │   ├── Jet.framework
│       │   │   └── Jet
│       │   ├── KeyboardArbiter.framework
│       │   │   └── KeyboardArbiter
│       │   ├── LanguageModeling.framework
│       │   │   └── LanguageModeling
│       │   ├── LatentSemanticMapping.framework
│       │   │   └── LatentSemanticMapping
│       │   ├── LegacyGameKit.framework
│       │   │   └── LegacyGameKit
│       │   ├── MIME.framework
│       │   │   └── MIME
│       │   ├── MMCS.framework
│       │   │   └── MMCS
│       │   ├── MMCSServices.framework
│       │   │   └── MMCSServices
│       │   ├── MPUFoundation.framework
│       │   │   └── MPUFoundation
│       │   ├── MTLCompiler.framework
│       │   │   └── MTLCompiler
│       │   ├── MailServices.framework
│       │   │   └── MailServices
│       │   ├── ManagedConfiguration.framework
│       │   │   ├── MDM.framework
│       │   │   │   └── MDM
│       │   │   └── ManagedConfiguration
│       │   ├── MapsSupport.framework
│       │   │   └── MapsSupport
│       │   ├── Marco.framework
│       │   │   └── Marco
│       │   ├── MarkupUI.framework
│       │   │   └── MarkupUI
│       │   ├── MediaControlSender.framework
│       │   │   └── MediaControlSender
│       │   ├── MediaLibrary.framework
│       │   │   └── MediaLibrary
│       │   ├── MediaLibraryCore.framework
│       │   │   └── MediaLibraryCore
│       │   ├── MediaPlatform.framework
│       │   │   └── MediaPlatform
│       │   ├── MediaPlayerUI.framework
│       │   │   └── MediaPlayerUI
│       │   ├── MediaRemote.framework
│       │   │   └── MediaRemote
│       │   ├── MediaServices.framework
│       │   │   └── MediaServices
│       │   ├── MediaSocial.framework
│       │   │   └── MediaSocial
│       │   ├── MediaStream.framework
│       │   │   └── MediaStream
│       │   ├── Message.framework
│       │   │   ├── MailServices
│       │   │   │   ├── IMAP.framework
│       │   │   │   │   └── IMAP
│       │   │   │   └── POP.framework
│       │   │   │       └── POP
│       │   │   └── Message
│       │   ├── MessageProtection.framework
│       │   │   └── MessageProtection
│       │   ├── MessageSupport.framework
│       │   │   └── MessageSupport
│       │   ├── MetalTools.framework
│       │   │   └── MetalTools
│       │   ├── MobileAccessoryUpdater.framework
│       │   │   └── MobileAccessoryUpdater
│       │   ├── MobileActivation.framework
│       │   │   └── MobileActivation
│       │   ├── MobileAsset.framework
│       │   │   └── MobileAsset
│       │   ├── MobileAssetUpdater.framework
│       │   │   └── MobileAssetUpdater
│       │   ├── MobileBackup.framework
│       │   │   └── MobileBackup
│       │   ├── MobileBluetooth.framework
│       │   │   └── MobileBluetooth
│       │   ├── MobileContainerManager.framework
│       │   │   └── MobileContainerManager
│       │   ├── MobileDelete.framework
│       │   │   └── MobileDelete
│       │   ├── MobileDeviceLink.framework
│       │   │   └── MobileDeviceLink
│       │   ├── MobileIcons.framework
│       │   │   └── MobileIcons
│       │   ├── MobileInstallation.framework
│       │   │   └── MobileInstallation
│       │   ├── MobileKeyBag.framework
│       │   │   └── MobileKeyBag
│       │   ├── MobileLookup.framework
│       │   │   └── MobileLookup
│       │   ├── MobileObliteration.framework
│       │   │   └── MobileObliteration
│       │   ├── MobileSoftwareUpdate.framework
│       │   │   └── MobileSoftwareUpdate
│       │   ├── MobileSpotlightIndex.framework
│       │   │   └── MobileSpotlightIndex
│       │   ├── MobileStorage.framework
│       │   │   └── MobileStorage
│       │   ├── MobileSync.framework
│       │   │   └── MobileSync
│       │   ├── MobileSystemServices.framework
│       │   │   └── MobileSystemServices
│       │   ├── MobileTimer.framework
│       │   │   └── MobileTimer
│       │   ├── MobileWiFi.framework
│       │   │   └── MobileWiFi
│       │   ├── MultitouchSupport.framework
│       │   │   └── MultitouchSupport
│       │   ├── MusicCarDisplayUI.framework
│       │   │   └── MusicCarDisplayUI
│       │   ├── MusicLibrary.framework
│       │   │   └── MusicLibrary
│       │   ├── MusicStoreUI.framework
│       │   │   └── MusicStoreUI
│       │   ├── NCLaunchStats.framework
│       │   │   └── NCLaunchStats
│       │   ├── NanoAppRegistry.framework
│       │   │   └── NanoAppRegistry
│       │   ├── NanoAudioControl.framework
│       │   │   └── NanoAudioControl
│       │   ├── NanoBackup.framework
│       │   │   └── NanoBackup
│       │   ├── NanoComplicationSettings.framework
│       │   │   └── NanoComplicationSettings
│       │   ├── NanoGlanceSettings.framework
│       │   │   └── NanoGlanceSettings
│       │   ├── NanoLeash.framework
│       │   │   └── NanoLeash
│       │   ├── NanoMailKitServer.framework
│       │   │   └── NanoMailKitServer
│       │   ├── NanoMediaRemote.framework
│       │   │   └── NanoMediaRemote
│       │   ├── NanoMusicSync.framework
│       │   │   └── NanoMusicSync
│       │   ├── NanoPassKit.framework
│       │   │   └── NanoPassKit
│       │   ├── NanoPhonePerfTesting.framework
│       │   │   └── NanoPhonePerfTesting
│       │   ├── NanoPreferencesSync.framework
│       │   │   └── NanoPreferencesSync
│       │   ├── NanoRegistry.framework
│       │   │   └── NanoRegistry
│       │   ├── NanoResourceGrabber.framework
│       │   │   └── NanoResourceGrabber
│       │   ├── NanoSetupUISupport.framework
│       │   │   └── NanoSetupUISupport
│       │   ├── NanoSystemSettings.framework
│       │   │   └── NanoSystemSettings
│       │   ├── NanoTimeKitCompanion.framework
│       │   │   └── NanoTimeKitCompanion
│       │   ├── NearField.framework
│       │   │   └── NearField
│       │   ├── NetAppsUtilitiesUI.framework
│       │   │   └── NetAppsUtilitiesUI
│       │   ├── Netrb.framework
│       │   │   └── Netrb
│       │   ├── Network.framework
│       │   │   └── Network
│       │   ├── NetworkStatistics.framework
│       │   │   └── NetworkStatistics
│       │   ├── Notes.framework
│       │   │   └── Notes
│       │   ├── NotesShared.framework
│       │   │   └── NotesShared
│       │   ├── NotificationsUI.framework
│       │   │   └── NotificationsUI
│       │   ├── OAuth.framework
│       │   │   └── OAuth
│       │   ├── OfficeImport.framework
│       │   │   └── OfficeImport
│       │   ├── OpenCL.framework
│       │   │   ├── ImageFormats
│       │   │   │   ├── float_rgba.dylib
│       │   │   │   ├── half_rgba.dylib
│       │   │   │   ├── sfixed14_rgba.dylib
│       │   │   │   ├── sint16_rgba.dylib
│       │   │   │   ├── sint32_rgba.dylib
│       │   │   │   ├── sint8_rgba.dylib
│       │   │   │   ├── uint16_rgba.dylib
│       │   │   │   ├── uint32_rgba.dylib
│       │   │   │   ├── uint8_rgba.dylib
│       │   │   │   ├── unorm16_rgba.dylib
│       │   │   │   ├── unorm8_bgra.dylib
│       │   │   │   ├── unorm8_rgba.dylib
│       │   │   │   ├── unorm8_rgx.dylib
│       │   │   │   └── unorm8_rx.dylib
│       │   │   ├── OpenCL
│       │   │   ├── libCLVMCPUPlugin.dylib
│       │   │   └── libcldcpuengine.dylib
│       │   ├── PBBridgeSupport.framework
│       │   │   └── PBBridgeSupport
│       │   ├── PacketFilter.framework
│       │   │   └── PacketFilter
│       │   ├── PairedSync.framework
│       │   │   └── PairedSync
│       │   ├── PairedUnlock.framework
│       │   │   └── PairedUnlock
│       │   ├── Parsec.framework
│       │   │   └── Parsec
│       │   ├── ParsecSubscriptionServiceSupport.framework
│       │   │   └── ParsecSubscriptionServiceSupport
│       │   ├── PassKitCore.framework
│       │   │   └── PassKitCore
│       │   ├── Pegasus.framework
│       │   │   └── Pegasus
│       │   ├── PerformanceAnalysis.framework
│       │   │   └── PerformanceAnalysis
│       │   ├── PersistentConnection.framework
│       │   │   └── PersistentConnection
│       │   ├── PhotoBoothEffects.framework
│       │   │   └── PhotoBoothEffects
│       │   ├── PhotoEditSupport.framework
│       │   │   └── PhotoEditSupport
│       │   ├── PhotoLibrary.framework
│       │   │   └── PhotoLibrary
│       │   ├── PhotoLibraryServices.framework
│       │   │   └── PhotoLibraryServices
│       │   ├── PhotosFormats.framework
│       │   │   └── PhotosFormats
│       │   ├── PhotosPlayer.framework
│       │   │   └── PhotosPlayer
│       │   ├── PhysicsKit.framework
│       │   │   └── PhysicsKit
│       │   ├── PlugInKit.framework
│       │   │   └── PlugInKit
│       │   ├── PowerLog.framework
│       │   │   └── PowerLog
│       │   ├── PowerlogAccounting.framework
│       │   │   └── PowerlogAccounting
│       │   ├── PowerlogControl.framework
│       │   │   └── PowerlogControl
│       │   ├── PowerlogCore.framework
│       │   │   └── PowerlogCore
│       │   ├── PowerlogDatabaseReader.framework
│       │   │   └── PowerlogDatabaseReader
│       │   ├── PowerlogFullOperators.framework
│       │   │   └── PowerlogFullOperators
│       │   ├── PowerlogHelperdOperators.framework
│       │   │   └── PowerlogHelperdOperators
│       │   ├── PowerlogLiteOperators.framework
│       │   │   └── PowerlogLiteOperators
│       │   ├── Preferences.framework
│       │   │   └── Preferences
│       │   ├── PreferencesUI.framework
│       │   │   └── PreferencesUI
│       │   ├── PrintKit.framework
│       │   │   └── PrintKit
│       │   ├── ProgressUI.framework
│       │   │   └── ProgressUI
│       │   ├── ProofReader.framework
│       │   │   └── ProofReader
│       │   ├── ProtectedCloudStorage.framework
│       │   │   └── ProtectedCloudStorage
│       │   ├── ProtocolBuffer.framework
│       │   │   └── ProtocolBuffer
│       │   ├── PrototypeTools.framework
│       │   │   └── PrototypeTools
│       │   ├── ProxiedCrashCopierClient.framework
│       │   │   └── ProxiedCrashCopierClient
│       │   ├── Quagga.framework
│       │   │   └── Quagga
│       │   ├── QuickLookThumbnailing.framework
│       │   │   └── QuickLookThumbnailing
│       │   ├── RDSupport.framework
│       │   │   └── RDSupport
│       │   ├── RTCReporting.framework
│       │   │   └── RTCReporting
│       │   ├── Radio.framework
│       │   │   └── Radio
│       │   ├── RadioUI.framework
│       │   │   └── RadioUI
│       │   ├── RemindersUI.framework
│       │   │   └── RemindersUI
│       │   ├── RemoteMediaServices.framework
│       │   │   └── RemoteMediaServices
│       │   ├── RemoteUI.framework
│       │   │   └── RemoteUI
│       │   ├── ResponseKit.framework
│       │   │   └── ResponseKit
│       │   ├── SAObjects.framework
│       │   │   └── SAObjects
│       │   ├── SafariSafeBrowsing.framework
│       │   │   └── SafariSafeBrowsing
│       │   ├── SafariShared.framework
│       │   │   └── SafariShared
│       │   ├── ScreenReaderBrailleDriver.framework
│       │   │   └── ScreenReaderBrailleDriver
│       │   ├── ScreenReaderCore.framework
│       │   │   └── ScreenReaderCore
│       │   ├── ScreenReaderOutput.framework
│       │   │   └── ScreenReaderOutput
│       │   ├── ScreenReaderOutputServer.framework
│       │   │   └── ScreenReaderOutputServer
│       │   ├── Search.framework
│       │   │   └── Search
│       │   ├── SearchUI.framework
│       │   │   └── SearchUI
│       │   ├── ServerAccounts.framework
│       │   │   └── ServerAccounts
│       │   ├── ServerDocsProtocol.framework
│       │   │   └── ServerDocsProtocol
│       │   ├── ServiceManagement.framework
│       │   │   └── ServiceManagement
│       │   ├── SetupAssistant.framework
│       │   │   └── SetupAssistant
│       │   ├── SetupAssistantUI.framework
│       │   │   └── SetupAssistantUI
│       │   ├── SharedWebCredentials.framework
│       │   │   └── SharedWebCredentials
│       │   ├── Sharing.framework
│       │   │   └── Sharing
│       │   ├── SiriTasks.framework
│       │   │   └── SiriTasks
│       │   ├── SiriUI.framework
│       │   │   └── SiriUI
│       │   ├── SiriUICore.framework
│       │   │   └── SiriUICore
│       │   ├── SlideshowKit.framework
│       │   │   ├── Frameworks
│       │   │   │   ├── OpusFoundation.framework
│       │   │   │   │   └── OpusFoundation
│       │   │   │   └── OpusKit.framework
│       │   │   │       └── OpusKit
│       │   │   └── SlideshowKit
│       │   ├── SoftwareBehaviorServices.framework
│       │   │   └── SoftwareBehaviorServices
│       │   ├── SoftwareUpdateBridge.framework
│       │   │   └── SoftwareUpdateBridge
│       │   ├── SoftwareUpdateServices.framework
│       │   │   └── SoftwareUpdateServices
│       │   ├── Speech.framework
│       │   │   └── Speech
│       │   ├── SplashBoard.framework
│       │   │   └── SplashBoard
│       │   ├── Spotlight.framework
│       │   │   └── Spotlight
│       │   ├── SpotlightDaemon.framework
│       │   │   └── SpotlightDaemon
│       │   ├── SpotlightReceiver.framework
│       │   │   └── SpotlightReceiver
│       │   ├── SpotlightUI.framework
│       │   │   └── SpotlightUI
│       │   ├── SpringBoardFoundation.framework
│       │   │   └── SpringBoardFoundation
│       │   ├── SpringBoardServices.framework
│       │   │   └── SpringBoardServices
│       │   ├── SpringBoardUI.framework
│       │   │   └── SpringBoardUI
│       │   ├── SpringBoardUIServices.framework
│       │   │   └── SpringBoardUIServices
│       │   ├── Stocks.framework
│       │   │   └── Stocks
│       │   ├── StoreBookkeeper.framework
│       │   │   └── StoreBookkeeper
│       │   ├── StoreBookkeeperClient.framework
│       │   │   └── StoreBookkeeperClient
│       │   ├── StoreKitUI.framework
│       │   │   └── StoreKitUI
│       │   ├── StoreServices.framework
│       │   │   └── StoreServices
│       │   ├── StoreServicesCore.framework
│       │   │   └── StoreServicesCore
│       │   ├── StreamingZip.framework
│       │   │   └── StreamingZip
│       │   ├── Symbolication.framework
│       │   │   └── Symbolication
│       │   ├── Symptoms.framework
│       │   │   └── Frameworks
│       │   │       ├── ManagedEvent.framework
│       │   │       │   └── ManagedEvent
│       │   │       ├── SymptomAnalytics.framework
│       │   │       │   └── SymptomAnalytics
│       │   │       ├── SymptomEvaluator.framework
│       │   │       │   └── SymptomEvaluator
│       │   │       ├── SymptomPresentationFeed.framework
│       │   │       │   └── SymptomPresentationFeed
│       │   │       ├── SymptomPresentationLite.framework
│       │   │       │   └── SymptomPresentationLite
│       │   │       └── SymptomReporter.framework
│       │   │           └── SymptomReporter
│       │   ├── SyncedDefaults.framework
│       │   │   └── SyncedDefaults
│       │   ├── TCC.framework
│       │   │   └── TCC
│       │   ├── TelephonyRPC.framework
│       │   │   └── TelephonyRPC
│       │   ├── TelephonyUI.framework
│       │   │   └── TelephonyUI
│       │   ├── TelephonyUtilities.framework
│       │   │   └── TelephonyUtilities
│       │   ├── TelephonyXPCClient.framework
│       │   │   └── TelephonyXPCClient
│       │   ├── TelephonyXPCServer.framework
│       │   │   └── TelephonyXPCServer
│       │   ├── TextInput.framework
│       │   │   ├── KBLayouts_iPhone.dylib
│       │   │   └── TextInput
│       │   ├── TextToSpeech.framework
│       │   │   └── TextToSpeech
│       │   ├── ThermalMonitorExporter.framework
│       │   │   └── ThermalMonitorExporter
│       │   ├── Tips.framework
│       │   │   └── Tips
│       │   ├── ToneKit.framework
│       │   │   └── ToneKit
│       │   ├── ToneLibrary.framework
│       │   │   └── ToneLibrary
│       │   ├── TouchRemote.framework
│       │   │   └── TouchRemote
│       │   ├── UIAccessibility.framework
│       │   │   └── UIAccessibility
│       │   ├── UIFoundation.framework
│       │   │   └── UIFoundation
│       │   ├── UITriggerVC.framework
│       │   │   └── UITriggerVC
│       │   ├── UserActivity.framework
│       │   │   └── UserActivity
│       │   ├── UserFS.framework
│       │   │   └── UserFS
│       │   ├── UserNotification.framework
│       │   │   └── UserNotification
│       │   ├── UserNotificationServices.framework
│       │   │   └── UserNotificationServices
│       │   ├── VPNUtilities.framework
│       │   │   └── VPNUtilities
│       │   ├── VUSocialUpload.framework
│       │   │   └── VUSocialUpload
│       │   ├── VectorKit.framework
│       │   │   └── VectorKit
│       │   ├── VideoProcessing.framework
│       │   │   └── VideoProcessing
│       │   ├── VideoUpload.framework
│       │   │   └── VideoUpload
│       │   ├── VisualAlert.framework
│       │   │   └── VisualAlert
│       │   ├── VisualVoicemail.framework
│       │   │   ├── ACDS.vvservice
│       │   │   │   └── ACDS
│       │   │   ├── IMAP.vvservice
│       │   │   │   └── IMAP
│       │   │   └── VisualVoicemail
│       │   ├── VoiceMemos.framework
│       │   │   └── VoiceMemos
│       │   ├── VoiceServices.framework
│       │   │   └── VoiceServices
│       │   ├── VoiceTrigger.framework
│       │   │   └── VoiceTrigger
│       │   ├── VoiceTriggerUI.framework
│       │   │   └── VoiceTriggerUI
│       │   ├── VoicemailStore.framework
│       │   │   └── VoicemailStore
│       │   ├── Weather.framework
│       │   │   └── Weather
│       │   ├── WeatherUI.framework
│       │   │   └── WeatherUI
│       │   ├── WebApp.framework
│       │   │   └── WebApp
│       │   ├── WebBookmarks.framework
│       │   │   └── WebBookmarks
│       │   ├── WebContentAnalysis.framework
│       │   │   └── WebContentAnalysis
│       │   ├── WebCore.framework
│       │   │   └── WebCore
│       │   ├── WebInspector.framework
│       │   │   └── WebInspector
│       │   ├── WebKit.framework
│       │   │   └── WebKit
│       │   ├── WebKitLegacy.framework
│       │   │   └── WebKitLegacy
│       │   ├── WebUI.framework
│       │   │   └── WebUI
│       │   ├── WelcomeKit.framework
│       │   │   └── WelcomeKit
│       │   ├── WelcomeKitCore.framework
│       │   │   └── WelcomeKitCore
│       │   ├── WelcomeKitUI.framework
│       │   │   └── WelcomeKitUI
│       │   ├── WiFiCloudSyncEngine.framework
│       │   │   └── WiFiCloudSyncEngine
│       │   ├── WiFiLogCapture.framework
│       │   │   └── WiFiLogCapture
│       │   ├── WirelessCoexManager.framework
│       │   │   └── WirelessCoexManager
│       │   ├── WirelessDiagnostics.framework
│       │   │   └── WirelessDiagnostics
│       │   ├── WirelessProximity.framework
│       │   │   └── WirelessProximity
│       │   ├── XPCKit.framework
│       │   │   └── XPCKit
│       │   ├── XPCService.framework
│       │   │   └── XPCService
│       │   ├── YouTube.framework
│       │   │   └── YouTube
│       │   ├── iAdCore.framework
│       │   │   └── iAdCore
│       │   ├── iAdDeveloper.framework
│       │   │   └── iAdDeveloper
│       │   ├── iAdServices.framework
│       │   │   └── iAdServices
│       │   ├── iCalendar.framework
│       │   │   └── iCalendar
│       │   ├── iCloudNotification.framework
│       │   │   └── iCloudNotification
│       │   ├── iOSDiagnostics.framework
│       │   │   └── iOSDiagnostics
│       │   ├── iOSDiagnosticsSupport.framework
│       │   │   └── iOSDiagnosticsSupport
│       │   ├── iPhotoMigrationSupport.framework
│       │   │   └── iPhotoMigrationSupport
│       │   ├── iTunesStore.framework
│       │   │   └── iTunesStore
│       │   ├── iTunesStoreUI.framework
│       │   │   └── iTunesStoreUI
│       │   ├── kperf.framework
│       │   │   └── kperf
│       │   ├── kperfdata.framework
│       │   │   └── kperfdata
│       │   ├── oncrpc.framework
│       │   │   └── oncrpc
│       │   └── vCard.framework
│       │       └── vCard
│       ├── ProceduralWallpaper
│       │   └── ProceduralWallpapers.bundle
│       │       └── ProceduralWallpapers
│       ├── PublishingBundles
│       │   └── PublishToYouTube.bundle
│       │       └── PublishToYouTube
│       ├── SearchBundles
│       │   ├── AddressBook.searchBundle
│       │   │   └── AddressBook
│       │   └── MobileNotes.searchBundle
│       │       └── MobileNotes
│       ├── SpringBoardPlugins
│       │   ├── Assistant.uibundle
│       │   │   └── Assistant
│       │   ├── ChatKit.servicebundle
│       │   │   └── ChatKit
│       │   ├── IncomingCall.servicebundle
│       │   │   └── IncomingCall
│       │   ├── NowPlayingArtLockScreen.lockbundle
│       │   │   └── NowPlayingArtLockScreen
│       │   ├── SIMToolkitUI.servicebundle
│       │   │   └── SIMToolkitUI
│       │   ├── StoreServicesPlugin.servicebundle
│       │   │   └── StoreServicesPlugin
│       │   └── VoiceMemosLockScreen.lockbundle
│       │       └── VoiceMemosLockScreen
│       ├── TextInput
│       │   ├── TextInput_bn.bundle
│       │   │   └── TextInput_bn
│       │   ├── TextInput_bo.bundle
│       │   │   └── TextInput_bo
│       │   ├── TextInput_ca.bundle
│       │   │   └── TextInput_ca
│       │   ├── TextInput_chr.bundle
│       │   │   └── TextInput_chr
│       │   ├── TextInput_cs.bundle
│       │   │   └── TextInput_cs
│       │   ├── TextInput_de.bundle
│       │   │   └── TextInput_de
│       │   ├── TextInput_el.bundle
│       │   │   └── TextInput_el
│       │   ├── TextInput_emoji.bundle
│       │   │   └── TextInput_emoji
│       │   ├── TextInput_en.bundle
│       │   │   └── TextInput_en
│       │   ├── TextInput_fr.bundle
│       │   │   └── TextInput_fr
│       │   ├── TextInput_gu.bundle
│       │   │   └── TextInput_gu
│       │   ├── TextInput_haw.bundle
│       │   │   └── TextInput_haw
│       │   ├── TextInput_he.bundle
│       │   │   └── TextInput_he
│       │   ├── TextInput_hi.bundle
│       │   │   └── TextInput_hi
│       │   ├── TextInput_intl.bundle
│       │   │   └── TextInput_intl
│       │   ├── TextInput_it.bundle
│       │   │   └── TextInput_it
│       │   ├── TextInput_ja.bundle
│       │   │   └── TextInput_ja
│       │   ├── TextInput_ko.bundle
│       │   │   └── TextInput_ko
│       │   ├── TextInput_mr.bundle
│       │   │   └── TextInput_mr
│       │   ├── TextInput_pa.bundle
│       │   │   └── TextInput_pa
│       │   ├── TextInput_pt.bundle
│       │   │   └── TextInput_pt
│       │   ├── TextInput_sk.bundle
│       │   │   └── TextInput_sk
│       │   ├── TextInput_ta.bundle
│       │   │   └── TextInput_ta
│       │   ├── TextInput_te.bundle
│       │   │   └── TextInput_te
│       │   ├── TextInput_th.bundle
│       │   │   └── TextInput_th
│       │   ├── TextInput_tr.bundle
│       │   │   └── TextInput_tr
│       │   ├── TextInput_ur.bundle
│       │   │   └── TextInput_ur
│       │   ├── TextInput_vi.bundle
│       │   │   └── TextInput_vi
│       │   ├── TextInput_zh.bundle
│       │   │   └── TextInput_zh
│       │   └── libTextInputCore.dylib
│       ├── UserEventPlugins
│       │   └── AppleHDQGasGauge.plugin
│       │       └── AppleHDQGasGauge
│       ├── VideoDecoders
│       │   ├── H264H6.videodecoder
│       │   ├── JPEGH1.videodecoder
│       │   ├── MP4VH6.videodecoder
│       │   ├── Slim.videodecoder
│       │   └── VCH263.videodecoder
│       ├── VideoEncoders
│       │   ├── H264H4.videoencoder
│       │   ├── H264H7.videoencoder
│       │   ├── JPEGH1.videoencoder
│       │   ├── Slim.videoencoder
│       │   └── VCH263.videoencoder
│       ├── VideoProcessors
│       │   ├── GyroVideoStabilization.videoprocessor
│       │   ├── HDR.videoprocessor
│       │   ├── RawReprocess.videoprocessor
│       │   └── SIS.videoprocessor
│       ├── VoiceServices
│       │   └── PlugIns
│       │       ├── VoiceDial.vsplugin
│       │       │   └── VoiceDial
│       │       └── iPod.vsplugin
│       │           └── iPod
│       └── WeeAppPlugins
│           └── AttributionWeeApp.bundle
│               └── AttributionWeeApp
└── usr
    └── lib
        ├── CarrierBundleUtilities.dylib
        ├── IOABPLib.dylib
        ├── PN548.dylib
        ├── PN548_API.dylib
        ├── PN548_HAL.dylib
        ├── libATCommandStudioDynamic.dylib
        ├── libAWDProtobuf.dylib
        ├── libAWDProtobufAWD.dylib
        ├── libAWDProtobufBluetooth.dylib
        ├── libAWDProtobufCATM.dylib
        ├── libAWDProtobufFacetime.dylib
        ├── libAWDProtobufFacetimeiMessage.dylib
        ├── libAWDProtobufGCK.dylib
        ├── libAWDProtobufLocation.dylib
        ├── libAWDProtobufTelephony.dylib
        ├── libAWDSupport.dylib
        ├── libAWDSupportConfig.dylib
        ├── libAWDSupportFramework.dylib
        ├── libAWDSupportInfo.dylib
        ├── libAXSafeCategoryBundle.dylib
        ├── libAXSpeechManager.dylib
        ├── libAccessibility.dylib
        ├── libAppPatch.dylib
        ├── libBBUpdaterDynamic.dylib
        ├── libBasebandManager.dylib
        ├── libBasebandPCI.dylib
        ├── libBasebandUSB.dylib
        ├── libCRFSuite.dylib
        ├── libCRFSuite0.12.dylib
        ├── libCTLogHelper.dylib
        ├── libCTWakeCommandParserDynamic.dylib
        ├── libChineseTokenizer.dylib
        ├── libDHCPServer.A.dylib
        ├── libDHCPServer.dylib
        ├── libETLDIAGLoggingDynamic.dylib
        ├── libETLDLFDynamic.dylib
        ├── libETLDLOADCoreDumpDynamic.dylib
        ├── libETLDLOADDynamic.dylib
        ├── libETLDMCDynamic.dylib
        ├── libETLDynamic.dylib
        ├── libETLEFSDumpDynamic.dylib
        ├── libETLSAHDynamic.dylib
        ├── libETLTransportDynamic.dylib
        ├── libFDR.dylib
        ├── libFDRDecode.dylib
        ├── libFosl_dynamic.dylib
        ├── libGestureServer.dylib
        ├── libH5Dynamic.dylib
        ├── libHDLCDynamic.dylib
        ├── libIOAccessoryManager.dylib
        ├── libMatch.1.dylib
        ├── libMatch.dylib
        ├── libMobileCheckpoint.dylib
        ├── libMobileGestalt.dylib
        ├── libMobileGestaltExtensions.dylib
        ├── libQLCharts.dylib
        ├── libQMIParserDynamic.dylib
        ├── libReverseProxyDevice.dylib
        ├── libSystem.B.dylib
        ├── libSystem.dylib
        ├── libTelephonyBasebandBulkUSBDynamic.dylib
        ├── libTelephonyBasebandDynamic.dylib
        ├── libTelephonyCommandDrivers.dylib
        ├── libTelephonyDebugDynamic.dylib
        ├── libTelephonyIOKitDynamic.dylib
        ├── libTelephonyPCIDynamic.dylib
        ├── libTelephonyUSBDynamic.dylib
        ├── libTelephonyUtilDynamic.dylib
        ├── libThaiTokenizer.dylib
        ├── libWAPI.dylib
        ├── libacmobileshim.dylib
        ├── libafc.dylib
        ├── libamsupport.dylib
        ├── libarchive.2.dylib
        ├── libarchive.dylib
        ├── libassertion_launchd.dylib
        ├── libauthinstall.dylib
        ├── libbsm.0.dylib
        ├── libbsm.dylib
        ├── libbz2.1.0.5.dylib
        ├── libbz2.1.0.dylib
        ├── libbz2.dylib
        ├── libc++.1.dylib
        ├── libc++.dylib
        ├── libc++abi.dylib
        ├── libc.dylib
        ├── libcharset.1.0.0.dylib
        ├── libcharset.1.dylib
        ├── libcharset.dylib
        ├── libcmph.dylib
        ├── libcompression.dylib
        ├── libcoreroutine.dylib
        ├── libcupolicy.dylib
        ├── libcurses.dylib
        ├── libdbm.dylib
        ├── libdl.dylib
        ├── libdns_services.dylib
        ├── libedit.2.dylib
        ├── libedit.3.0.dylib
        ├── libedit.3.dylib
        ├── libedit.dylib
        ├── libenergytrace.dylib
        ├── libexslt.0.dylib
        ├── libexslt.dylib
        ├── libextension.dylib
        ├── libform.5.4.dylib
        ├── libform.dylib
        ├── libgermantok.dylib
        ├── libgll.dylib
        ├── libheimdal-asn1.dylib
        ├── libiconv.2.4.0.dylib
        ├── libiconv.2.dylib
        ├── libiconv.dylib
        ├── libicucore.A.dylib
        ├── libicucore.dylib
        ├── libinfo.dylib
        ├── libipconfig.dylib
        ├── libipsec.A.dylib
        ├── libipsec.dylib
        ├── liblangid.dylib
        ├── liblockdown.dylib
        ├── liblzma.5.dylib
        ├── liblzma.dylib
        ├── libm.dylib
        ├── libmarisa.dylib
        ├── libmav_ipc_router_dynamic.dylib
        ├── libmecab_em.dylib
        ├── libmecabra.dylib
        ├── libmis.dylib
        ├── libncurses.5.4.dylib
        ├── libncurses.5.dylib
        ├── libncurses.dylib
        ├── libnetwork.dylib
        ├── libnfshared.dylib
        ├── libobjc.A.dylib
        ├── libobjc.dylib
        ├── libomadm.dylib
        ├── libpcap.A.dylib
        ├── libpcap.dylib
        ├── libpoll.dylib
        ├── libprequelite.dylib
        ├── libproc.dylib
        ├── libprotobuf.dylib
        ├── libpthread.dylib
        ├── libresolv.9.dylib
        ├── libresolv.dylib
        ├── librpcsvc.dylib
        ├── libsandbox.1.dylib
        ├── libsandbox.dylib
        ├── libsp.dylib
        ├── libsqlite3.0.dylib
        ├── libsqlite3.dylib
        ├── libstdc++.6.dylib
        ├── libtidy.A.dylib
        ├── libtidy.dylib
        ├── libtzupdate.dylib
        ├── libutil.dylib
        ├── libutil1.0.dylib
        ├── libxml2.2.dylib
        ├── libxml2.dylib
        ├── libxslt.1.dylib
        ├── libxslt.dylib
        ├── libz.1.1.3.dylib
        ├── libz.1.2.5.dylib
        ├── libz.1.dylib
        ├── libz.dylib
        └── system
            ├── libcache.dylib
            ├── libcommonCrypto.dylib
            ├── libcompiler_rt.dylib
            ├── libcopyfile.dylib
            ├── libcorecrypto.dylib
            ├── libdispatch.dylib
            ├── libdyld.dylib
            ├── liblaunch.dylib
            ├── libmacho.dylib
            ├── libremovefile.dylib
            ├── libsystem_asl.dylib
            ├── libsystem_blocks.dylib
            ├── libsystem_c.dylib
            ├── libsystem_configuration.dylib
            ├── libsystem_containermanager.dylib
            ├── libsystem_coreservices.dylib
            ├── libsystem_coretls.dylib
            ├── libsystem_dnssd.dylib
            ├── libsystem_info.dylib
            ├── libsystem_kernel.dylib
            ├── libsystem_m.dylib
            ├── libsystem_malloc.dylib
            ├── libsystem_network.dylib
            ├── libsystem_networkextension.dylib
            ├── libsystem_notify.dylib
            ├── libsystem_platform.dylib
            ├── libsystem_pthread.dylib
            ├── libsystem_sandbox.dylib
            ├── libsystem_trace.dylib
            ├── libunwind.dylib
            ├── libvminterpose.dylib
            └── libxpc.dylib

769 directories, 1005 files
</code></pre>
</details>

# Tips

## `dsc_extractor.bundle` Can't work on Xcode10

On Apple Developer Forums:[dyld_shared_cache_extract_dylibs failed](https://forums.developer.apple.com/thread/108917).

Error information:

```sh
$ ./dsc_extractor dyld_shared_cache_arm64 arm64
Error: dyld shared cache code signature for page 0 is incorrect.
dyld_shared_cache_extract_dylibs_progress() => -1
```

**So the [dsc_extractor.bundle](https://github.com/madordie/dsc_extractor/blob/master/dsc_extractor.bundle) is the Xcode9 version.**

And [modify](https://github.com/madordie/dyld/commit/265727c18666f034c76e28706070fae04377eb82) the `./dyld/launch-cache/dsc_extractor.cpp`

## How to get dyld_shared_cache_arm64

- Obtained through iPhone firmware. Such as: https://ipsw.me/
- Obtained through jailbroken equipment. The path: `/System/Library/Caches/com.apple.dyld/dyld_shared_cache_arm64`
 
