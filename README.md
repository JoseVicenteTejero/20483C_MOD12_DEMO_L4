# 20483C_MOD12_DEMO_L4
Lesson 4: Versioning, Signing, and Deploying Assemblies

JOSE VICENTE TEJERO CALDERERA - 06/11/2020

RESUMEN
Demonstration: Signing and Installing an Assembly into the GAC
C:\20483\Allfiles\Mod12\Democode\Starter\FourthCoffee.Core\FourthCoffee.Core>generateKeyFile.cmd

C:\20483\Allfiles\Mod12\Democode\Starter\FourthCoffee.Core\FourthCoffee.Core>sn -k FourthCoffeeKeyFile.snk

Utilidad de nombre seguro de Microsoft (R) .NET Framework versión 4.0.30319.0
(c) Microsoft Corporation. Reservados todos los derechos.

Par de claves escrito en FourthCoffeeKeyFile.snk

C:\20483\Allfiles\Mod12\Democode\Starter\FourthCoffee.Core\FourthCoffee.Core>installAssemblyInGac.cmd

C:\20483\Allfiles\Mod12\Democode\Starter\FourthCoffee.Core\FourthCoffee.Core>gacutil -i bin\Debug\FourthCoffee.Core.dll
Microsoft (R) .NET Global Assembly Cache Utility.  Version 4.0.30319.0
(c) Microsoft Corporation. Reservados todos los derechos.

Ensamblado agregado correctamente a la caché

PROBLEMAS
Ninguno
