# Java_Eclipse_Maven_WindowsSetup

  ## Download:
* [ ] https://jdk.java.net/15/ (JDK Downloaden)
* [ ] https://gluonhq.com/products/javafx/ (JMODS Donwloaden)
* [ ] https://gluonhq.com/products/scene-builder/ (SceneBuilder Downloaden)
* [ ] https://wixtoolset.org/ (WiX Toolset exe Downloaden)

  ## JDK erstellen:
* [ ] openJDK und openJFX-JMods entpacken und nach C:/Java/ verschieben
* [ ] Windows+R
* [ ] cmd eingeben und Enter
* [ ] Terminal: cd c:/Java/jdk-15.0.1/bin/
* [ ] Terminal: 
	->jlink --output jdfx-15 --module-path  C:\Java\javafx-jmods-15.0.1 --add-modules
java.base,java.compiler,java.datatransfer,java.desktop,java.instrument,java.logging,java.management,java.management.rmi,java.naming,java.net.http,java.prefs,java.rmi,java.scripting,java.se,java.security.jgss,java.security.sasl,java.smartcardio,java.sql,java.sql.rowset,java.transaction.xa,java.xml.crypto,java.xml,jdk.accessibility,jdk.aot,jdk.attach,jdk.charsets,jdk.compiler,jdk.crypto.cryptoki,jdk.crypto.ec,jdk.dynalink,jdk.editpad,jdk.hotspot.agent,jdk.httpserver,jdk.incubator.foreign,jdk.incubator.jpackage,jdk.internal.ed,jdk.internal.jvmstat,jdk.internal.le,jdk.internal.opt,jdk.internal.vm.ci,jdk.internal.vm.compiler,jdk.internal.vm.compiler.management,jdk.jartool,jdk.javadoc,jdk.jcmd,jdk.jconsole,jdk.jdeps,jdk.jdi,jdk.jdwp.agent,jdk.jfr,jdk.jlink,jdk.jshell,jdk.jsobject,jdk.jstatd,jdk.localedata,jdk.management.agent,jdk.management.jfr,jdk.management,jdk.naming.dns,jdk.naming.rmi,jdk.net,jdk.nio.mapmode,jdk.sctp,jdk.security.auth,jdk.security.jgss,jdk.unsupported.desktop,jdk.unsupported,jdk.xml.dom,jdk.zipfs,javafx.base,javafx.controls,javafx.fxml,javafx.graphics,javafx.media,javafx.swing,javafx.web

  ## Eclipse installer starten:
* [ ] Eclipse für EE (Java Enterprise Entwickler auswählen)
* [ ] Bei JDK Ordner C:/Java/jdfx-15/
* [ ] Bei Installationspfad C:/Java/Eclipse
	
  ## SceneBuilder installieren

  ## Eclipse öffnen:
* [ ] Help -> Marketplace:
	-> e(fx)clipse installieren
* [ ] Window -> preferences:
* [ ] Auf javaFX kicken:
	-> Bei Scenebuilder die exe suche
	-> SDK C:/Java/jdfx-15

  ## WiX Toolset installieren
