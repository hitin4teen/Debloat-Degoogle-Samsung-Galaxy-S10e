# Debloat-Degoogle-Samsung-Galaxy-S10e

Known bugs:
<br />-for some reason samsung accessibility package is uninstalled, may be I'm blind. after reinstallation it is somewhat operational(no unknown problems for now)
<br />-at least some nfc apps seem to don't work, but passes nfc check app
<br />-to use bxActions you will need to reinstall Bixby Voice(after setting up bxActions you can disable it)
<br />-sound quality and effects button in sound and vibration doesn't work

Fixed:
<br />-microsoft launcher and swiftkey sign in failure

I have tried to delete every non crucial application, excluding those, that are required for booting device. Haven't yet thoroughly tested, use at your own risk. 
Applications install after debloating is possible through adb install command.

paste these commands in adb shell:

> <br />pm uninstall --user 0 com.amazon.fv
> <br />pm uninstall --user 0 com.amazon.kindle
> <br />pm uninstall --user 0 com.amazon.mShop.android
> <br />pm uninstall --user 0 com.amazon.mp3
> <br />pm uninstall --user 0 com.amazon.venezia
> <br />pm uninstall --user 0 com.android.backupconfirm
> <br />pm uninstall --user 0 com.android.bips
> <br />pm uninstall --user 0 com.android.chrome
> <br />pm uninstall --user 0 com.android.dreams.basic
> <br />pm uninstall --user 0 com.android.dreams.phototable
> <br />pm uninstall --user 0 com.android.dreams.phototable
> <br />pm uninstall --user 0 com.android.email
> <br />pm uninstall --user 0 com.android.exchange
> <br />pm uninstall --user 0 com.android.hotwordenrollment.okgoogle
> <br />pm uninstall --user 0 com.android.printspooler
> <br />pm uninstall --user 0 com.android.providers.partnerbookmarks
> <br />pm uninstall --user 0 com.android.providers.userdictionary
> <br />pm uninstall --user 0 com.android.sharedstoragebackup
> <br />pm uninstall --user 0 com.android.stk
> <br />pm uninstall --user 0 com.android.wallpaper.livepicker
> <br />pm uninstall --user 0 com.android.wallpapercropper
> <br />pm uninstall --user 0 com.audible.application
> <br />pm uninstall --user 0 com.blurb.checkout
> <br />pm uninstall --user 0 com.cequint.ecid
> <br />pm uninstall --user 0 com.cnn.mobile.android.phone.edgepanel
> <br />pm uninstall --user 0 com.diotek.sec.lookup.dictionary
> <br />pm uninstall --user 0 com.dsi.ant.plugins.antplus
> <br />pm uninstall --user 0 com.dsi.ant.sample.acquirechannels
> <br />pm uninstall --user 0 com.dsi.ant.server
> <br />pm uninstall --user 0 com.dsi.ant.service.socket
> <br />pm uninstall --user 0 com.enhance.gameservice
> <br />pm uninstall --user 0 com.facebook.appmanager
> <br />pm uninstall --user 0 com.facebook.katana
> <br />pm uninstall --user 0 com.facebook.services
> <br />pm uninstall --user 0 com.facebook.system
> <br />pm uninstall --user 0 com.flipboard.app
> <br />pm uninstall --user 0 com.flipboard.boxer.app
> <br />pm uninstall --user 0 com.google.android.apps.books
> <br />pm uninstall --user 0 com.google.android.apps.docs
> <br />pm uninstall --user 0 com.google.android.apps.magazines
> <br />pm uninstall --user 0 com.google.android.apps.maps
> <br />pm uninstall --user 0 com.google.android.apps.plus
> <br />pm uninstall --user 0 com.google.android.apps.tachyon
> <br />pm uninstall --user 0 com.google.android.apps.tachyon
> <br />pm uninstall --user 0 com.google.android.apps.youtube.music
> <br />pm uninstall --user 0 com.google.android.gm
> <br />pm uninstall --user 0 com.google.android.googlequicksearchbox
> <br />pm uninstall --user 0 com.google.android.printservice.recommendation
> <br />pm uninstall --user 0 com.google.android.talk
> <br />pm uninstall --user 0 com.google.android.tts
> <br />pm uninstall --user 0 com.google.android.videos
> <br />pm uninstall --user 0 com.google.android.videos
> <br />pm uninstall --user 0 com.google.android.youtube
> <br />pm uninstall --user 0 com.google.ar.core
> <br />pm uninstall --user 0 com.google.vr.vrcore
> <br />pm uninstall --user 0 com.gotv.nflgamecenter.us.lite
> <br />pm uninstall --user 0 com.hancom.office.editor.hidden
> <br />pm uninstall --user 0 com.hancom.office.editor.hidden
> <br />pm uninstall --user 0 com.imdb.mobile
> <br />pm uninstall --user 0 com.infraware.polarisoffice5
> <br />pm uninstall --user 0 com.linkedin.android
> <br />pm uninstall --user 0 com.microsoft.appmanager
> <br />pm uninstall --user 0 com.microsoft.office.excel
> <br />pm uninstall --user 0 com.microsoft.office.officehubrow
> <br />pm uninstall --user 0 com.microsoft.office.outlook
> <br />pm uninstall --user 0 com.microsoft.office.powerpoint
> <br />pm uninstall --user 0 com.microsoft.office.word
> <br />pm uninstall --user 0 com.microsoft.skydrive
> <br />pm uninstall --user 0 com.mobeam.barcodeService
> <br />pm uninstall --user 0 com.monotype.android.font.chococooky
> <br />pm uninstall --user 0 com.monotype.android.font.cooljazz
> <br />pm uninstall --user 0 com.monotype.android.font.foundation
> <br />pm uninstall --user 0 com.monotype.android.font.rosemary
> <br />pm uninstall --user 0 com.netflix.mediaclient
> <br />pm uninstall --user 0 com.nuance.swype.input
> <br />pm uninstall --user 0 com.osp.app.signin
> <br />pm uninstall --user 0 com.policydm
> <br />pm uninstall --user 0 com.samsung.SMT
> <br />pm uninstall --user 0 com.samsung.aasaservice
> <br />pm uninstall --user 0 com.samsung.android.aircommandmanager
> <br />pm uninstall --user 0 com.samsung.android.allshare.service.fileshare
> <br />pm uninstall --user 0 com.samsung.android.allshare.service.mediashare
> <br />pm uninstall --user 0 com.samsung.android.app.advsounddetector
> <br />pm uninstall --user 0 com.samsung.android.app.appsedge
> <br />pm uninstall --user 0 com.samsung.android.app.assistantmenu
> <br />pm uninstall --user 0 com.samsung.android.app.camera.sticker.facear.preload
> <br />pm uninstall --user 0 com.samsung.android.app.camera.sticker.facear3d.preload
> <br />pm uninstall --user 0 com.samsung.android.app.camera.sticker.facearavatar.preload
> <br />pm uninstall --user 0 com.samsung.android.app.camera.sticker.facearframe.preload
> <br />pm uninstall --user 0 com.samsung.android.app.camera.sticker.stamp.preload
> <br />pm uninstall --user 0 com.samsung.android.app.clipboardedge
> <br />pm uninstall --user 0 com.samsung.android.app.cocktailbarservice
> <br />pm uninstall --user 0 com.samsung.android.app.episodes
> <br />pm uninstall --user 0 com.samsung.android.app.filterinstaller
> <br />pm uninstall --user 0 com.samsung.android.app.galaxyfinder
> <br />pm uninstall --user 0 com.samsung.android.app.ledbackcover
> <br />pm uninstall --user 0 com.samsung.android.app.ledcoverdream
> <br />pm uninstall --user 0 com.samsung.android.app.memo
> <br />pm uninstall --user 0 com.samsung.android.app.mirrorlink
> <br />pm uninstall --user 0 com.samsung.android.app.notes
> <br />pm uninstall --user 0 com.samsung.android.app.notes
> <br />pm uninstall --user 0 com.samsung.android.app.reminder
> <br />pm uninstall --user 0 com.samsung.android.app.routines
> <br />pm uninstall --user 0 com.samsung.android.app.settings.bixby
> <br />pm uninstall --user 0 com.samsung.android.app.sharelive
> <br />pm uninstall --user 0 com.samsung.android.app.simplesharing
> <br />pm uninstall --user 0 com.samsung.android.app.soundpicker
> <br />pm uninstall --user 0 com.samsung.android.app.spage
> <br />pm uninstall --user 0 com.samsung.android.app.storyalbumwidget
> <br />pm uninstall --user 0 com.samsung.android.app.talkback
> <br />pm uninstall --user 0 com.samsung.android.app.taskedge
> <br />pm uninstall --user 0 com.samsung.android.app.tips
> <br />pm uninstall --user 0 com.samsung.android.app.vrsetupwizardstub
> <br />pm uninstall --user 0 com.samsung.android.app.watchmanager
> <br />pm uninstall --user 0 com.samsung.android.app.watchmanagerstub
> <br />pm uninstall --user 0 com.samsung.android.app.withtv
> <br />pm uninstall --user 0 com.samsung.android.ardrawing
> <br />pm uninstall --user 0 com.samsung.android.aremoji
> <br />pm uninstall --user 0 com.samsung.android.arzone
> <br />pm uninstall --user 0 com.samsung.android.authfw
> <br />pm uninstall --user 0 com.samsung.android.aware.service
> <br />pm uninstall --user 0 com.samsung.android.bbc.bbcagent
> <br />pm uninstall --user 0 com.samsung.android.beaconmanager
> <br />pm uninstall --user 0 com.samsung.android.calendar
> <br />pm uninstall --user 0 com.samsung.android.da.daagent
> <br />pm uninstall --user 0 com.samsung.android.dlp.service
> <br />pm uninstall --user 0 com.samsung.android.drivelink.stub
> <br />pm uninstall --user 0 com.samsung.android.easysetup
> <br />pm uninstall --user 0 com.samsung.android.fmm
> <br />pm uninstall --user 0 com.samsung.android.game.gamehome
> <br />pm uninstall --user 0 com.samsung.android.game.gametools
> <br />pm uninstall --user 0 com.samsung.android.game.gos
> <br />pm uninstall --user 0 com.samsung.android.gametuner.thin
> <br />pm uninstall --user 0 com.samsung.android.hmt.vrshell
> <br />pm uninstall --user 0 com.samsung.android.hmt.vrsvc
> <br />pm uninstall --user 0 com.samsung.android.keyguardwallpaperupdator
> <br />pm uninstall --user 0 com.samsung.android.kidsinstaller
> <br />pm uninstall --user 0 com.samsung.android.knox.analytics.uploader
> <br />pm uninstall --user 0 com.samsung.android.mateagent
> <br />pm uninstall --user 0 com.samsung.android.mdm
> <br />pm uninstall --user 0 com.samsung.android.mdx
> <br />pm uninstall --user 0 com.samsung.android.mdx.kit
> <br />pm uninstall --user 0 com.samsung.android.mdx.quickboard
> <br />pm uninstall --user 0 com.samsung.android.messaging
> <br />pm uninstall --user 0 com.samsung.android.mobileservice
> <br />pm uninstall --user 0 com.samsung.android.oneconnect
> <br />pm uninstall --user 0 com.samsung.android.oneconnect
> <br />pm uninstall --user 0 com.samsung.android.samsungpass
> <br />pm uninstall --user 0 com.samsung.android.samsungpassautofill
> <br />pm uninstall --user 0 com.samsung.android.scloud
> <br />pm uninstall --user 0 com.samsung.android.sdk.professionalaudio.utility.jammonitor
> <br />pm uninstall --user 0 com.samsung.android.server.iris
> <br />pm uninstall --user 0 com.samsung.android.service.livedrawing
> <br />pm uninstall --user 0 com.samsung.android.service.peoplestripe
> <br />pm uninstall --user 0 com.samsung.android.service.travel
> <br />pm uninstall --user 0 com.samsung.android.setting.multisound
> <br />pm uninstall --user 0 com.samsung.android.spdfnote
> <br />pm uninstall --user 0 com.samsung.android.stickercenter
> <br />pm uninstall --user 0 com.samsung.android.stickerplugin
> <br />pm uninstall --user 0 com.samsung.android.svoice
> <br />pm uninstall --user 0 com.samsung.android.svoiceime
> <br />pm uninstall --user 0 com.samsung.android.themecenter
> <br />pm uninstall --user 0 com.samsung.android.themestore
> <br />pm uninstall --user 0 com.samsung.android.tripwidget
> <br />pm uninstall --user 0 com.samsung.android.visionarapps
> <br />pm uninstall --user 0 com.samsung.android.visioncloudagent
> <br />pm uninstall --user 0 com.samsung.android.visionintelligence
> <br />pm uninstall --user 0 com.samsung.android.voc
> <br />pm uninstall --user 0 com.samsung.android.voicewakeup
> <br />pm uninstall --user 0 com.samsung.android.wellbeing
> <br />pm uninstall --user 0 com.samsung.android.widgetapp.yahooedge.finance
> <br />pm uninstall --user 0 com.samsung.android.widgetapp.yahooedge.sport
> <br />pm uninstall --user 0 com.samsung.app.highlightplayer
> <br />pm uninstall --user 0 com.samsung.daydream.customization
> <br />pm uninstall --user 0 com.samsung.dcmservice
> <br />pm uninstall --user 0 com.samsung.desktopsystemui
> <br />pm uninstall --user 0 com.samsung.enhanceservice
> <br />pm uninstall --user 0 com.samsung.faceservice
> <br />pm uninstall --user 0 com.samsung.fresco.logging
> <br />pm uninstall --user 0 com.samsung.groupcast
> <br />pm uninstall --user 0 com.samsung.hs20provider
> <br />pm uninstall --user 0 com.samsung.ipservice
> <br />pm uninstall --user 0 com.samsung.knox.appsupdateagent
> <br />pm uninstall --user 0 com.samsung.knox.rcp.components
> <br />pm uninstall --user 0 com.samsung.knox.securefolder
> <br />pm uninstall --user 0 com.samsung.knox.securefolder.setuppage
> <br />pm uninstall --user 0 com.samsung.safetyinformation
> <br />pm uninstall --user 0 com.samsung.sec.android.application.csc
> <br />pm uninstall --user 0 com.samsung.sree
> <br />pm uninstall --user 0 com.samsung.storyservice
> <br />pm uninstall --user 0 com.samsung.svoice.sync
> <br />pm uninstall --user 0 com.samsung.systemui.bixby
> <br />pm uninstall --user 0 com.samsung.systemui.bixby2
> <br />pm uninstall --user 0 com.samsung.ucs.agent.ese
> <br />pm uninstall --user 0 com.samsung.voiceserviceplatform
> <br />pm uninstall --user 0 com.sec.android.AutoPreconfig
> <br />pm uninstall --user 0 com.sec.android.Preconfig
> <br />pm uninstall --user 0 com.sec.android.RilServiceModeApp
> <br />pm uninstall --user 0 com.sec.android.app.DataCreate
> <br />pm uninstall --user 0 com.sec.android.app.SecSetupWizard
> <br />pm uninstall --user 0 com.sec.android.app.SmartClipEdgeService
> <br />pm uninstall --user 0 com.sec.android.app.apex
> <br />pm uninstall --user 0 com.sec.android.app.applinker
> <br />pm uninstall --user 0 com.sec.android.app.billing
> <br />pm uninstall --user 0 com.sec.android.app.bluetoothtest
> <br />pm uninstall --user 0 com.sec.android.app.chromecustomizations
> <br />pm uninstall --user 0 com.sec.android.app.clockpackage
> <br />pm uninstall --user 0 com.sec.android.app.desktoplauncher
> <br />pm uninstall --user 0 com.sec.android.app.dexonpc
> <br />pm uninstall --user 0 com.sec.android.app.factorykeystring
> <br />pm uninstall --user 0 com.sec.android.app.gamehub
> <br />pm uninstall --user 0 com.sec.android.app.hwmoduletest
> <br />pm uninstall --user 0 com.sec.android.app.magnifier
> <br />pm uninstall --user 0 com.sec.android.app.myfiles
> <br />pm uninstall --user 0 com.sec.android.app.ocr
> <br />pm uninstall --user 0 com.sec.android.app.parser
> <br />pm uninstall --user 0 com.sec.android.app.personalization
> <br />pm uninstall --user 0 com.sec.android.app.popupcalculator
> <br />pm uninstall --user 0 com.sec.android.app.popupcalculator
> <br />pm uninstall --user 0 com.sec.android.app.quicktool
> <br />pm uninstall --user 0 com.sec.android.app.ringtoneBR
> <br />pm uninstall --user 0 com.sec.android.app.safetyassurance
> <br />pm uninstall --user 0 com.sec.android.app.samsungapps
> <br />pm uninstall --user 0 com.sec.android.app.servicemodeapp
> <br />pm uninstall --user 0 com.sec.android.app.shealth
> <br />pm uninstall --user 0 com.sec.android.app.shealth
> <br />pm uninstall --user 0 com.sec.android.app.soundalive
> <br />pm uninstall --user 0 com.sec.android.app.sysscope
> <br />pm uninstall --user 0 com.sec.android.app.tfunlock
> <br />pm uninstall --user 0 com.sec.android.app.tourviewer
> <br />pm uninstall --user 0 com.sec.android.app.translator
> <br />pm uninstall --user 0 com.sec.android.app.ve.vebgm
> <br />pm uninstall --user 0 com.sec.android.app.wfdbroker
> <br />pm uninstall --user 0 com.sec.android.app.withtv
> <br />pm uninstall --user 0 com.sec.android.app.wlantest
> <br />pm uninstall --user 0 com.sec.android.cover.ledcover
> <br />pm uninstall --user 0 com.sec.android.daemonapp
> <br />pm uninstall --user 0 com.sec.android.desktopmode.uiservice
> <br />pm uninstall --user 0 com.sec.android.diagmonagent
> <br />pm uninstall --user 0 com.sec.android.easyMover
> <br />pm uninstall --user 0 com.sec.android.easyMover
> <br />pm uninstall --user 0 com.sec.android.easyMover.Agent
> <br />pm uninstall --user 0 com.sec.android.easyonehand
> <br />pm uninstall --user 0 com.sec.android.emergencylauncher
> <br />pm uninstall --user 0 com.sec.android.mimage.avatarstickers
> <br />pm uninstall --user 0 com.sec.android.mimage.gear360editor
> <br />pm uninstall --user 0 com.sec.android.mimage.photoretouching
> <br />pm uninstall --user 0 com.sec.android.ofviewer
> <br />pm uninstall --user 0 com.sec.android.omc
> <br />pm uninstall --user 0 com.sec.android.preloadinstaller
> <br />pm uninstall --user 0 com.sec.android.provider.snote
> <br />pm uninstall --user 0 com.sec.android.providers.security
> <br />pm uninstall --user 0 com.sec.android.providers.tasks
> <br />pm uninstall --user 0 com.sec.android.sdhms
> <br />pm uninstall --user 0 com.sec.android.service.health
> <br />pm uninstall --user 0 com.sec.android.sidesync30
> <br />pm uninstall --user 0 com.sec.android.splitsound
> <br />pm uninstall --user 0 com.sec.android.uibcvirtualsoftkey
> <br />pm uninstall --user 0 com.sec.android.widgetapp.diotek.smemo
> <br />pm uninstall --user 0 com.sec.android.widgetapp.easymodecontactswidget
> <br />pm uninstall --user 0 com.sec.android.widgetapp.samsungapps
> <br />pm uninstall --user 0 com.sec.app.TransmitPowerService
> <br />pm uninstall --user 0 com.sec.automation
> <br />pm uninstall --user 0 com.sec.bcservice
> <br />pm uninstall --user 0 com.sec.downloadablekeystore
> <br />pm uninstall --user 0 com.sec.enterprise.knox.attestation
> <br />pm uninstall --user 0 com.sec.enterprise.knox.cloudmdm.smdms
> <br />pm uninstall --user 0 com.sec.enterprise.mdm.services.simpin
> <br />pm uninstall --user 0 com.sec.enterprise.mdm.vpn
> <br />pm uninstall --user 0 com.sec.epdgtestapp
> <br />pm uninstall --user 0 com.sec.everglades
> <br />pm uninstall --user 0 com.sec.everglades.update
> <br />pm uninstall --user 0 com.sec.factory
> <br />pm uninstall --user 0 com.sec.factory.camera
> <br />pm uninstall --user 0 com.sec.factory.iris.usercamera
> <br />pm uninstall --user 0 com.sec.hearingadjust
> <br />pm uninstall --user 0 com.sec.kidsplat.installer
> <br />pm uninstall --user 0 com.sec.knox.foldercontainer
> <br />pm uninstall --user 0 com.sec.knox.knoxsetupwizardclient
> <br />pm uninstall --user 0 com.sec.knox.switcher
> <br />pm uninstall --user 0 com.sec.location.nsflp2
> <br />pm uninstall --user 0 com.sec.mldapchecker
> <br />pm uninstall --user 0 com.sec.modem.settings
> <br />pm uninstall --user 0 com.sec.providers.assisteddialing
> <br />pm uninstall --user 0 com.sec.readershub
> <br />pm uninstall --user 0 com.sec.smartcard.manager
> <br />pm uninstall --user 0 com.sec.spen.flashannotate
> <br />pm uninstall --user 0 com.sec.spp.push
> <br />pm uninstall --user 0 com.sec.sve
> <br />pm uninstall --user 0 com.sec.usbsettings
> <br />pm uninstall --user 0 com.sec.vowifispg
> <br />pm uninstall --user 0 com.sec.yosemite.phone
> <br />pm uninstall --user 0 com.sem.factoryapp
> <br />pm uninstall --user 0 com.singtel.mysingtel
> <br />pm uninstall --user 0 com.skms.android.agent
> <br />pm uninstall --user 0 com.skype.raider
> <br />pm uninstall --user 0 com.test.LTEfunctionality
> <br />pm uninstall --user 0 com.touchtype.swiftkey
> <br />pm uninstall --user 0 com.tripadvisor.tripadvisor
> <br />pm uninstall --user 0 com.trustonic.tuiservice
> <br />pm uninstall --user 0 com.tv.peel.samsung.app
> <br />pm uninstall --user 0 com.vlingo.midas
> <br />pm uninstall --user 0 com.wssnps
> <br />pm uninstall --user 0 com.yelp.android.samsungedge

> <br />pm uninstall --user 0 com.android.chrome
> <br />pm uninstall --user 0 com.google.android.calendar
> <br />pm uninstall --user 0 com.google.android.vending
> <br />pm uninstall --user 0 com.google.android.gms
> <br />pm uninstall --user 0 com.google.android.gm
> <br />pm uninstall --user 0 com.google.android.youtube
> <br />pm uninstall --user 0 com.google.android.youtube
> <br />pm uninstall --user 0 com.google.android.apps.maps
> <br />pm uninstall --user 0 com.google.android.apps.photos
> <br />pm uninstall --user 0 com.google.android.talk
> <br />pm uninstall --user 0 com.google.android.music
> <br />pm uninstall --user 0 com.google.android.videos
> <br />pm uninstall --user 0 com.google.android.feedback
> <br />pm uninstall --user 0 com.google.android.apps.docs.oem
> <br />pm uninstall --user 0 com.google.android.tts
> <br />pm uninstall --user 0 com.google.android.configupdater
> <br />pm uninstall --user 0 com.google.android.partnersetup
> <br />pm uninstall --user 0 com.google.android.backuptransport
> <br />pm uninstall --user 0 com.google.android.apps.tachyon
> <br />pm uninstall --user 0 com.android.vending

Only uninstall if you will use something other than it:
<br />Samsung keyboard
> <br />pm uninstall --user 0 com.samsung.android.honeyboard

<br />Samsung browser
> <br />pm uninstall --user 0 com.samsung.android.app.sbrowseredge
> <br />pm uninstall --user 0 com.sec.android.app.sbrowser

<br />Samsung mail
> <br />pm uninstall --user 0 com.samsung.android.email.provider

<br />Samsung gallery
> <br />pm uninstall --user 0 com.sec.android.gallery3d

<br />Samsung contacts
> <br />pm uninstall --user 0 com.samsung.android.app.contacts

<br />Samsung phone
> <br />pm uninstall --user 0 com.samsung.android.dialer


might cause problems:
<br />Samsung pay(may be cause of nfc not working in some apps, haven't tested this enough yet to make conclusion)
> <br />pm uninstall --user 0 com.samsung.android.spay
> <br />pm uninstall --user 0 com.samsung.android.spayfw

<br />Bixby(removing causes a third-party app bxActions used for bixby button remapping to not work)
> <br />pm uninstall --user 0 com.samsung.android.bixby.agent
> <br />pm uninstall --user 0 com.samsung.android.bixby.agent.dummy
> <br />pm uninstall --user 0 com.samsung.android.bixby.es.globalaction
> <br />pm uninstall --user 0 com.samsung.android.bixby.plmsync
> <br />pm uninstall --user 0 com.samsung.android.bixby.service
> <br />pm uninstall --user 0 com.samsung.android.bixby.voiceinput
> <br />pm uninstall --user 0 com.samsung.android.bixby.wakeup
> <br />pm uninstall --user 0 com.samsung.android.bixbyvision.framework

<br />Device care(removing causes power saving option not available through settings)
> <br />pm uninstall --user 0 com.samsung.android.lool

<br />One UI home(Samsung launcher) removes ability to look at recent apps and disables home gesture(go back gesture works fine)
> <br />pm uninstall --user 0 com.sec.android.app.launcher

final result
![alt text](https://raw.githubusercontent.com/hitin4teen/Debloat-Degoogle-Samsung-adb/main/N5boZVr2FQ8.jpg)
