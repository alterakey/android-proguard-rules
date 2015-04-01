# ProGuard rules for Android

(C) 2015 Takahiro Yoshimura.  All rights reserved.


0. HOW TO USE
==============

    buildTypes {
        release {
            // Assuming pulled this repository as 'pp'
            proguardFiles 'pp/core.pro', 'pp/com.facebook.pro', 'pp/package.name.pro', ...
            minifyEnabled true
        }
    }

1. BUGS
=======

Insanely lacking packages.  Contributions are welcome.

2. LICENSE
==========

The MIT license.  Please refer to LICENSE.txt.