# Example-generator

[Acceleo tutorial - Getting started](https://wiki.eclipse.org/Acceleo/Getting_Started)

### Possible troubles

#### Exception in thread "main" java.lang.NoClassDefFoundError: com/google/common/base/Predicate

From the FAQ of [Acceleo](https://wiki.eclipse.org/Acceleo/FAQ#Exception_in_thread_.22main.22_java.lang.NoClassDefFoundError:_com.2Fgoogle.2Fcommon.2Fbase.2FPredicate). Add com.google.collect as a dependency of the generator. (MANIFEST.MF -> Dependencies tab -> Add -> com.google.collect)

(In Windows at C:\\Users\<your-user>\.p2\plugins)

### Run the generator

Go to **umlToBeans.mtl**, right click, *Run as -> Launch Acceleo Application*

