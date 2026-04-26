[astraadm@192 ~]$ sudo dnf groupinstall "Development Tools"

We trust you have received the usual lecture from the local System
Administrator. It usually boils down to these three things:

    #1) Respect the privacy of others.
    #2) Think before you type.
    #3) With great power comes great responsibility.

For security reasons, the password you type will not be visible.

[sudo] password for astraadm:
CentOS Stream 9 - BaseOS                                                   815 kB/s | 8.9 MB     00:11
CentOS Stream 9 - AppStream                                                493 kB/s |  27 MB     00:56
CentOS Stream 9 - Extras packages                                          1.4 kB/s |  21 kB     00:14
Dependencies resolved.
===========================================================================================================
 Package                                Architecture  Version                       Repository        Size
===========================================================================================================
Installing group/module packages:
 asciidoc                               noarch        9.1.0-3.el9                   appstream        261 k
 autoconf                               noarch        2.69-41.el9                   appstream        681 k
 automake                               noarch        1.16.2-8.el9                  appstream        689 k
 bison                                  x86_64        3.7.4-5.el9                   appstream        943 k
 byacc                                  x86_64        2.0.20210109-4.el9            appstream         89 k
 diffstat                               x86_64        1.64-6.el9                    appstream         44 k
 flex                                   x86_64        2.6.4-9.el9                   appstream        313 k
 gcc                                    x86_64        11.5.0-14.el9                 appstream         32 M
 gcc-c++                                x86_64        11.5.0-14.el9                 appstream         13 M
 gdb                                    x86_64        16.3-3.el9                    appstream        147 k
 git                                    x86_64        2.52.0-1.el9                  appstream         39 k
 glibc-devel                            x86_64        2.34-262.el9                  appstream         38 k
 intltool                               noarch        0.51.0-20.el9                 appstream         56 k
 jna                                    x86_64        5.6.0-8.el9                   appstream        270 k
 libtool                                x86_64        2.4.6-46.el9                  appstream        581 k
 ltrace                                 x86_64        0.7.91-43.el9                 appstream        138 k
 make                                   x86_64        1:4.3-8.el9                   baseos           536 k
 patchutils                             x86_64        0.4.2-7.el9                   appstream        107 k
 perl-Fedora-VSP                        noarch        0.001-23.el9                  appstream         24 k
 perl-generators                        noarch        1.13-1.el9                    appstream         16 k
 pesign                                 x86_64        115-6.el9                     appstream        175 k
 redhat-rpm-config                      noarch        210-1.el9                     appstream         70 k
 rpm-build                              x86_64        4.16.1.3-40.el9               appstream         66 k
 rpm-sign                               x86_64        4.16.1.3-40.el9               baseos            17 k
 source-highlight                       x86_64        3.1.9-12.el9                  appstream        681 k
 systemtap                              x86_64        5.4-4.el9                     appstream        4.9 k
 valgrind                               x86_64        1:3.26.0-5.el9                appstream        3.3 M
 valgrind-devel                         x86_64        1:3.26.0-5.el9                appstream         49 k
Installing dependencies:
 annobin                                x86_64        12.98-2.el9                   appstream        1.1 M
 boost-filesystem                       x86_64        1.75.0-13.el9                 appstream         55 k
 boost-regex                            x86_64        1.75.0-13.el9                 appstream        275 k
 boost-system                           x86_64        1.75.0-13.el9                 appstream         11 k
 boost-thread                           x86_64        1.75.0-13.el9                 appstream         53 k
 copy-jdk-configs                       noarch        4.0-3.el9                     appstream         28 k
 debugedit                              x86_64        5.0-11.el9                    appstream         77 k
 docbook-dtds                           noarch        1.0-79.el9                    appstream        361 k
 docbook-style-xsl                      noarch        1.79.2-16.el9                 appstream        1.6 M
 dwz                                    x86_64        0.16-1.el9                    appstream        134 k
 dyninst                                x86_64        13.0.0-1.el9                  appstream        3.7 M
 efi-srpm-macros                        noarch        6-4.el9                       appstream         21 k
 efivar-libs                            x86_64        38-3.el9                      baseos           121 k
 elfutils                               x86_64        0.194-1.el9                   baseos           603 k
 elfutils-devel                         x86_64        0.194-1.el9                   appstream         49 k
 elfutils-libelf-devel                  x86_64        0.194-1.el9                   appstream         79 k
 fonts-srpm-macros                      noarch        1:2.0.5-7.el9.1               appstream         28 k
 gcc-plugin-annobin                     x86_64        11.5.0-14.el9                 appstream         37 k
 gdb-headless                           x86_64        16.3-3.el9                    appstream        5.1 M
 gettext-common-devel                   noarch        0.21-8.el9                    appstream        406 k
 gettext-devel                          x86_64        0.21-8.el9                    appstream        213 k
 ghc-srpm-macros                        noarch        1.5.0-6.el9                   appstream        8.8 k
 git-core                               x86_64        2.52.0-1.el9                  appstream        5.0 M
 git-core-doc                           noarch        2.52.0-1.el9                  appstream        3.1 M
 glibc-headers                          x86_64        2.34-262.el9                  appstream        547 k
 go-srpm-macros                         noarch        3.8.1-1.el9                   appstream         27 k
 graphviz                               x86_64        2.44.0-26.el9                 appstream        3.3 M
 gtk2                                   x86_64        2.24.33-8.el9                 appstream        3.5 M
 ibus-gtk2                              x86_64        1.5.25-6.el9                  appstream         24 k
 java-1.8.0-openjdk-headless            x86_64        1:1.8.0.482.b08-3.el9         appstream         33 M
 javapackages-filesystem                noarch        6.4.0-1.el9                   appstream         13 k
 kernel-headers                         x86_64        5.14.0-694.el9                appstream        1.9 M
 kernel-srpm-macros                     noarch        1.0-14.el9                    appstream         14 k
 libXaw                                 x86_64        1.0.13-19.el9                 appstream        198 k
 libipt                                 x86_64        2.0.4-3.el9                   appstream         57 k
 libstdc++-devel                        x86_64        11.5.0-14.el9                 appstream        2.4 M
 libxcrypt-devel                        x86_64        4.4.18-3.el9                  appstream         29 k
 libzstd-devel                          x86_64        1.5.5-1.el9                   appstream         51 k
 lksctp-tools                           x86_64        1.0.19-2.el9                  baseos            94 k
 lua                                    x86_64        5.4.4-4.el9                   appstream        188 k
 lua-posix                              x86_64        35.0-8.el9                    appstream        151 k
 lua-srpm-macros                        noarch        1-6.el9                       appstream        9.5 k
 m4                                     x86_64        1.4.19-1.el9                  appstream        300 k
 mkfontscale                            x86_64        1.2.1-3.el9                   appstream         32 k
 mokutil                                x86_64        2:0.7.2-4.el9                 baseos            47 k
 nss-tools                              x86_64        3.112.0-8.el9                 appstream        446 k
 ocaml-srpm-macros                      noarch        6-6.el9                       appstream        8.8 k
 openblas-srpm-macros                   noarch        2-11.el9                      appstream        8.4 k
 openssl-devel                          x86_64        1:3.5.5-1.el9                 appstream        4.8 M
 patch                                  x86_64        2.7.6-16.el9                  appstream        128 k
 perl-Error                             noarch        1:0.17029-7.el9               appstream         42 k
 perl-File-Compare                      noarch        1.100.600-483.el9             appstream         13 k
 perl-File-Copy                         noarch        2.34-483.el9                  appstream         20 k
 perl-Git                               noarch        2.52.0-1.el9                  appstream         37 k
 perl-TermReadKey                       x86_64        2.38-11.el9                   appstream         37 k
 perl-Thread-Queue                      noarch        3.14-460.el9                  appstream         22 k
 perl-XML-Parser                        x86_64        2.46-10.el9                   appstream        238 k
 perl-lib                               x86_64        0.65-483.el9                  appstream         15 k
 perl-macros                            noarch        4:5.32.1-483.el9              appstream         10 k
 perl-srpm-macros                       noarch        1-41.el9                      appstream        9.1 k
 perl-threads                           x86_64        1:2.25-460.el9                appstream         58 k
 perl-threads-shared                    x86_64        1.61-460.el9                  appstream         45 k
 pyproject-srpm-macros                  noarch        1.18.5-1.el9                  appstream         12 k
 python-srpm-macros                     noarch        3.9-54.el9                    appstream         18 k
 qt5-srpm-macros                        noarch        5.15.9-1.el9                  appstream        8.8 k
 rust-srpm-macros                       noarch        17-4.el9                      appstream         10 k
 sgml-common                            noarch        0.6.3-58.el9                  appstream         60 k
 systemtap-client                       x86_64        5.4-4.el9                     appstream        4.1 M
 systemtap-devel                        x86_64        5.4-4.el9                     appstream        2.4 M
 systemtap-runtime                      x86_64        5.4-4.el9                     appstream        457 k
 tbb                                    x86_64        2020.3-9.el9                  appstream        168 k
 tzdata-java                            noarch        2026a-1.el9                   appstream        223 k
 xorg-x11-fonts-ISO8859-1-100dpi        noarch        7.5-33.el9                    appstream        1.1 M
 xz-devel                               x86_64        5.2.5-8.el9                   appstream         55 k
 zlib-devel                             x86_64        1.2.11-41.el9                 appstream         45 k
 zstd                                   x86_64        1.5.5-1.el9                   baseos           464 k
Installing weak dependencies:
 adwaita-gtk2-theme                     x86_64        3.28-14.el9                   appstream        213 k
 kernel-devel                           x86_64        5.14.0-694.el9                appstream         21 M
 libcanberra-gtk2                       x86_64        0.30-27.el9                   appstream         26 k
 perl-version                           x86_64        7:0.99.28-4.el9               appstream         63 k
 valgrind-docs                          x86_64        1:3.26.0-5.el9                appstream        1.5 M
 valgrind-gdb                           x86_64        1:3.26.0-5.el9                appstream        127 k
 valgrind-scripts                       x86_64        1:3.26.0-5.el9                appstream         67 k
Installing Groups:
 Development Tools

Transaction Summary
===========================================================================================================
Install  111 Packages

Total download size: 161 M
Installed size: 542 M
Is this ok [y/N]: y
Downloading Packages:
(1/111): efivar-libs-38-3.el9.x86_64.rpm                                   204 kB/s | 121 kB     00:00
(2/111): lksctp-tools-1.0.19-2.el9.x86_64.rpm                              125 kB/s |  94 kB     00:00
(3/111): mokutil-0.7.2-4.el9.x86_64.rpm                                    203 kB/s |  47 kB     00:00
(4/111): rpm-sign-4.16.1.3-40.el9.x86_64.rpm                               134 kB/s |  17 kB     00:00
(5/111): elfutils-0.194-1.el9.x86_64.rpm                                   355 kB/s | 603 kB     00:01
(6/111): make-4.3-8.el9.x86_64.rpm                                         453 kB/s | 536 kB     00:01
(7/111): adwaita-gtk2-theme-3.28-14.el9.x86_64.rpm                         612 kB/s | 213 kB     00:00
(8/111): zstd-1.5.5-1.el9.x86_64.rpm                                       452 kB/s | 464 kB     00:01
(9/111): asciidoc-9.1.0-3.el9.noarch.rpm                                   599 kB/s | 261 kB     00:00
(10/111): annobin-12.98-2.el9.x86_64.rpm                                   772 kB/s | 1.1 MB     00:01
(11/111): autoconf-2.69-41.el9.noarch.rpm                                  530 kB/s | 681 kB     00:01
(12/111): boost-filesystem-1.75.0-13.el9.x86_64.rpm                        517 kB/s |  55 kB     00:00
(13/111): automake-1.16.2-8.el9.noarch.rpm                                 626 kB/s | 689 kB     00:01
(14/111): boost-system-1.75.0-13.el9.x86_64.rpm                             51 kB/s |  11 kB     00:00
(15/111): boost-regex-1.75.0-13.el9.x86_64.rpm                             738 kB/s | 275 kB     00:00
(16/111): boost-thread-1.75.0-13.el9.x86_64.rpm                            391 kB/s |  53 kB     00:00
(17/111): bison-3.7.4-5.el9.x86_64.rpm                                     1.1 MB/s | 943 kB     00:00
(18/111): byacc-2.0.20210109-4.el9.x86_64.rpm                              260 kB/s |  89 kB     00:00
(19/111): debugedit-5.0-11.el9.x86_64.rpm                                  288 kB/s |  77 kB     00:00
(20/111): diffstat-1.64-6.el9.x86_64.rpm                                   162 kB/s |  44 kB     00:00
(21/111): copy-jdk-configs-4.0-3.el9.noarch.rpm                             47 kB/s |  28 kB     00:00
(22/111): dwz-0.16-1.el9.x86_64.rpm                                        152 kB/s | 134 kB     00:00
(23/111): docbook-dtds-1.0-79.el9.noarch.rpm                               286 kB/s | 361 kB     00:01
(24/111): efi-srpm-macros-6-4.el9.noarch.rpm                               162 kB/s |  21 kB     00:00
(25/111): elfutils-devel-0.194-1.el9.x86_64.rpm                            298 kB/s |  49 kB     00:00
(26/111): docbook-style-xsl-1.79.2-16.el9.noarch.rpm                       1.1 MB/s | 1.6 MB     00:01
(27/111): elfutils-libelf-devel-0.194-1.el9.x86_64.rpm                     449 kB/s |  79 kB     00:00
(28/111): fonts-srpm-macros-2.0.5-7.el9.1.noarch.rpm                       112 kB/s |  28 kB     00:00
(29/111): flex-2.6.4-9.el9.x86_64.rpm                                      747 kB/s | 313 kB     00:00
(30/111): dyninst-13.0.0-1.el9.x86_64.rpm                                  967 kB/s | 3.7 MB     00:03
(31/111): gcc-plugin-annobin-11.5.0-14.el9.x86_64.rpm                      349 kB/s |  37 kB     00:00
(32/111): gdb-16.3-3.el9.x86_64.rpm                                        549 kB/s | 147 kB     00:00
(33/111): gdb-headless-16.3-3.el9.x86_64.rpm                               1.4 MB/s | 5.1 MB     00:03
(34/111): gettext-common-devel-0.21-8.el9.noarch.rpm                       1.3 MB/s | 406 kB     00:00
(35/111): gettext-devel-0.21-8.el9.x86_64.rpm                              1.2 MB/s | 213 kB     00:00
(36/111): ghc-srpm-macros-1.5.0-6.el9.noarch.rpm                            80 kB/s | 8.8 kB     00:00
(37/111): git-2.52.0-1.el9.x86_64.rpm                                      246 kB/s |  39 kB     00:00
(38/111): gcc-c++-11.5.0-14.el9.x86_64.rpm                                 1.2 MB/s |  13 MB     00:10
(39/111): git-core-2.52.0-1.el9.x86_64.rpm                                 1.4 MB/s | 5.0 MB     00:03
(40/111): glibc-devel-2.34-262.el9.x86_64.rpm                              286 kB/s |  38 kB     00:00
(41/111): glibc-headers-2.34-262.el9.x86_64.rpm                            1.4 MB/s | 547 kB     00:00
(42/111): go-srpm-macros-3.8.1-1.el9.noarch.rpm                            258 kB/s |  27 kB     00:00
(43/111): git-core-doc-2.52.0-1.el9.noarch.rpm                             2.2 MB/s | 3.1 MB     00:01
(44/111): gtk2-2.24.33-8.el9.x86_64.rpm                                    2.4 MB/s | 3.5 MB     00:01
(45/111): graphviz-2.44.0-26.el9.x86_64.rpm                                1.8 MB/s | 3.3 MB     00:01
(46/111): ibus-gtk2-1.5.25-6.el9.x86_64.rpm                                266 kB/s |  24 kB     00:00
(47/111): intltool-0.51.0-20.el9.noarch.rpm                                309 kB/s |  56 kB     00:00
(48/111): javapackages-filesystem-6.4.0-1.el9.noarch.rpm                    44 kB/s |  13 kB     00:00
(49/111): jna-5.6.0-8.el9.x86_64.rpm                                       1.1 MB/s | 270 kB     00:00
(50/111): gcc-11.5.0-14.el9.x86_64.rpm                                     1.6 MB/s |  32 MB     00:20
(51/111): kernel-headers-5.14.0-694.el9.x86_64.rpm                         1.2 MB/s | 1.9 MB     00:01
(52/111): kernel-srpm-macros-1.0-14.el9.noarch.rpm                         146 kB/s |  14 kB     00:00
(53/111): libXaw-1.0.13-19.el9.x86_64.rpm                                  678 kB/s | 198 kB     00:00
(54/111): libcanberra-gtk2-0.30-27.el9.x86_64.rpm                          201 kB/s |  26 kB     00:00
(55/111): libipt-2.0.4-3.el9.x86_64.rpm                                    454 kB/s |  57 kB     00:00
(56/111): libstdc++-devel-11.5.0-14.el9.x86_64.rpm                         1.6 MB/s | 2.4 MB     00:01
(57/111): libtool-2.4.6-46.el9.x86_64.rpm                                  1.5 MB/s | 581 kB     00:00
(58/111): libxcrypt-devel-4.4.18-3.el9.x86_64.rpm                          300 kB/s |  29 kB     00:00
(59/111): libzstd-devel-1.5.5-1.el9.x86_64.rpm                             342 kB/s |  51 kB     00:00
(60/111): kernel-devel-5.14.0-694.el9.x86_64.rpm                           2.0 MB/s |  21 MB     00:10
(61/111): ltrace-0.7.91-43.el9.x86_64.rpm                                  671 kB/s | 138 kB     00:00
(62/111): lua-5.4.4-4.el9.x86_64.rpm                                       652 kB/s | 188 kB     00:00
(63/111): lua-posix-35.0-8.el9.x86_64.rpm                                  545 kB/s | 151 kB     00:00
(64/111): lua-srpm-macros-1-6.el9.noarch.rpm                                41 kB/s | 9.5 kB     00:00
(65/111): m4-1.4.19-1.el9.x86_64.rpm                                       872 kB/s | 300 kB     00:00
(66/111): mkfontscale-1.2.1-3.el9.x86_64.rpm                               119 kB/s |  32 kB     00:00
(67/111): ocaml-srpm-macros-6-6.el9.noarch.rpm                              35 kB/s | 8.8 kB     00:00
(68/111): nss-tools-3.112.0-8.el9.x86_64.rpm                               1.2 MB/s | 446 kB     00:00
(69/111): openblas-srpm-macros-2-11.el9.noarch.rpm                          65 kB/s | 8.4 kB     00:00
(70/111): patch-2.7.6-16.el9.x86_64.rpm                                    365 kB/s | 128 kB     00:00
(71/111): patchutils-0.4.2-7.el9.x86_64.rpm                                916 kB/s | 107 kB     00:00
(72/111): perl-Error-0.17029-7.el9.noarch.rpm                              298 kB/s |  42 kB     00:00
(73/111): perl-Fedora-VSP-0.001-23.el9.noarch.rpm                          246 kB/s |  24 kB     00:00
(74/111): perl-File-Compare-1.100.600-483.el9.noarch.rpm                    68 kB/s |  13 kB     00:00
(75/111): perl-File-Copy-2.34-483.el9.noarch.rpm                           182 kB/s |  20 kB     00:00
(76/111): perl-Git-2.52.0-1.el9.noarch.rpm                                 207 kB/s |  37 kB     00:00
(77/111): perl-TermReadKey-2.38-11.el9.x86_64.rpm                          359 kB/s |  37 kB     00:00
(78/111): perl-Thread-Queue-3.14-460.el9.noarch.rpm                        164 kB/s |  22 kB     00:00
(79/111): perl-XML-Parser-2.46-10.el9.x86_64.rpm                           1.0 MB/s | 238 kB     00:00
(80/111): perl-generators-1.13-1.el9.noarch.rpm                             86 kB/s |  16 kB     00:00
(81/111): perl-lib-0.65-483.el9.x86_64.rpm                                 126 kB/s |  15 kB     00:00
(82/111): perl-macros-5.32.1-483.el9.noarch.rpm                             69 kB/s |  10 kB     00:00
(83/111): perl-srpm-macros-1-41.el9.noarch.rpm                              96 kB/s | 9.1 kB     00:00
(84/111): openssl-devel-3.5.5-1.el9.x86_64.rpm                             2.1 MB/s | 4.8 MB     00:02
(85/111): java-1.8.0-openjdk-headless-1.8.0.482.b08-3.el9.x86_64.rpm       2.3 MB/s |  33 MB     00:14
(86/111): perl-threads-2.25-460.el9.x86_64.rpm                             347 kB/s |  58 kB     00:00
(87/111): perl-threads-shared-1.61-460.el9.x86_64.rpm                      143 kB/s |  45 kB     00:00
(88/111): perl-version-0.99.28-4.el9.x86_64.rpm                            112 kB/s |  63 kB     00:00
(89/111): pyproject-srpm-macros-1.18.5-1.el9.noarch.rpm                     24 kB/s |  12 kB     00:00
(90/111): qt5-srpm-macros-5.15.9-1.el9.noarch.rpm                           60 kB/s | 8.8 kB     00:00
(91/111): python-srpm-macros-3.9-54.el9.noarch.rpm                          45 kB/s |  18 kB     00:00
(92/111): pesign-115-6.el9.x86_64.rpm                                      172 kB/s | 175 kB     00:01
(93/111): redhat-rpm-config-210-1.el9.noarch.rpm                           204 kB/s |  70 kB     00:00
(94/111): rust-srpm-macros-17-4.el9.noarch.rpm                              35 kB/s |  10 kB     00:00
(95/111): sgml-common-0.6.3-58.el9.noarch.rpm                              218 kB/s |  60 kB     00:00
(96/111): rpm-build-4.16.1.3-40.el9.x86_64.rpm                             121 kB/s |  66 kB     00:00
(97/111): systemtap-5.4-4.el9.x86_64.rpm                                    11 kB/s | 4.9 kB     00:00
(98/111): source-highlight-3.1.9-12.el9.x86_64.rpm                         435 kB/s | 681 kB     00:01
(99/111): systemtap-runtime-5.4-4.el9.x86_64.rpm                           1.4 MB/s | 457 kB     00:00
(100/111): tbb-2020.3-9.el9.x86_64.rpm                                     914 kB/s | 168 kB     00:00
(101/111): tzdata-java-2026a-1.el9.noarch.rpm                              1.1 MB/s | 223 kB     00:00
(102/111): systemtap-devel-5.4-4.el9.x86_64.rpm                            1.1 MB/s | 2.4 MB     00:02
(103/111): valgrind-devel-3.26.0-5.el9.x86_64.rpm                          615 kB/s |  49 kB     00:00
(104/111): valgrind-docs-3.26.0-5.el9.x86_64.rpm                           1.7 MB/s | 1.5 MB     00:00
(105/111): valgrind-3.26.0-5.el9.x86_64.rpm                                2.0 MB/s | 3.3 MB     00:01
(106/111): valgrind-gdb-3.26.0-5.el9.x86_64.rpm                            1.6 MB/s | 127 kB     00:00
(107/111): valgrind-scripts-3.26.0-5.el9.x86_64.rpm                        359 kB/s |  67 kB     00:00
(108/111): xz-devel-5.2.5-8.el9.x86_64.rpm                                 207 kB/s |  55 kB     00:00
(109/111): systemtap-client-5.4-4.el9.x86_64.rpm                           966 kB/s | 4.1 MB     00:04
(110/111): zlib-devel-1.2.11-41.el9.x86_64.rpm                             245 kB/s |  45 kB     00:00
(111/111): xorg-x11-fonts-ISO8859-1-100dpi-7.5-33.el9.noarch.rpm           631 kB/s | 1.1 MB     00:01
-----------------------------------------------------------------------------------------------------------
Total                                                                      3.7 MB/s | 161 MB     00:43
CentOS Stream 9 - BaseOS                                                   1.1 MB/s | 1.6 kB     00:00
Importing GPG key 0x8483C65D:
 Userid     : "CentOS (CentOS Official Signing Key) <security@centos.org>"
 Fingerprint: 99DB 70FA E1D7 CE22 7FB6 4882 05B5 55B3 8483 C65D
 From       : /etc/pki/rpm-gpg/RPM-GPG-KEY-centosofficial
Is this ok [y/N]: y
Key imported successfully
Running transaction check
Transaction check succeeded.
Running transaction test
Transaction test succeeded.
Running transaction
  Running scriptlet: copy-jdk-configs-4.0-3.el9.noarch                                                 1/1
  Running scriptlet: java-1.8.0-openjdk-headless-1:1.8.0.482.b08-3.el9.x86_64                          1/1
  Preparing        :                                                                                   1/1
  Installing       : boost-system-1.75.0-13.el9.x86_64                                               1/111
  Installing       : perl-File-Copy-2.34-483.el9.noarch                                              2/111
  Installing       : patch-2.7.6-16.el9.x86_64                                                       3/111
  Installing       : m4-1.4.19-1.el9.x86_64                                                          4/111
  Installing       : make-1:4.3-8.el9.x86_64                                                         5/111
  Installing       : zlib-devel-1.2.11-41.el9.x86_64                                                 6/111
  Installing       : perl-threads-1:2.25-460.el9.x86_64                                              7/111
  Installing       : perl-File-Compare-1.100.600-483.el9.noarch                                      8/111
  Installing       : autoconf-2.69-41.el9.noarch                                                     9/111
  Installing       : libzstd-devel-1.5.5-1.el9.x86_64                                               10/111
  Installing       : elfutils-libelf-devel-0.194-1.el9.x86_64                                       11/111
  Installing       : javapackages-filesystem-6.4.0-1.el9.noarch                                     12/111
  Installing       : git-core-2.52.0-1.el9.x86_64                                                   13/111
  Installing       : dwz-0.16-1.el9.x86_64                                                          14/111
  Installing       : elfutils-0.194-1.el9.x86_64                                                    15/111
  Installing       : efivar-libs-38-3.el9.x86_64                                                    16/111
  Installing       : mokutil-2:0.7.2-4.el9.x86_64                                                   17/111
  Installing       : git-core-doc-2.52.0-1.el9.noarch                                               18/111
  Installing       : perl-threads-shared-1.61-460.el9.x86_64                                        19/111
  Installing       : perl-Thread-Queue-3.14-460.el9.noarch                                          20/111
  Installing       : automake-1.16.2-8.el9.noarch                                                   21/111
  Installing       : bison-3.7.4-5.el9.x86_64                                                       22/111
  Installing       : flex-2.6.4-9.el9.x86_64                                                        23/111
  Installing       : boost-filesystem-1.75.0-13.el9.x86_64                                          24/111
  Installing       : boost-thread-1.75.0-13.el9.x86_64                                              25/111
  Installing       : ibus-gtk2-1.5.25-6.el9.x86_64                                                  26/111
  Installing       : libcanberra-gtk2-0.30-27.el9.x86_64                                            27/111
  Installing       : gtk2-2.24.33-8.el9.x86_64                                                      28/111
  Installing       : adwaita-gtk2-theme-3.28-14.el9.x86_64                                          29/111
  Installing       : xz-devel-5.2.5-8.el9.x86_64                                                    30/111
  Installing       : elfutils-devel-0.194-1.el9.x86_64                                              31/111
  Installing       : valgrind-docs-1:3.26.0-5.el9.x86_64                                            32/111
  Installing       : tzdata-java-2026a-1.el9.noarch                                                 33/111
  Installing       : tbb-2020.3-9.el9.x86_64                                                        34/111
  Installing       : dyninst-13.0.0-1.el9.x86_64                                                    35/111
  Running scriptlet: dyninst-13.0.0-1.el9.x86_64                                                    35/111
  Running scriptlet: systemtap-runtime-5.4-4.el9.x86_64                                             36/111
Creating group 'stapusr' with GID 156.
Creating group 'stapsys' with GID 157.
Creating group 'stapdev' with GID 158.
Creating group 'stapunpriv' with GID 159.
Creating user 'stapunpriv' (systemtap unprivileged user) with UID 159 and GID 159.

  Installing       : systemtap-runtime-5.4-4.el9.x86_64                                             36/111
  Running scriptlet: systemtap-runtime-5.4-4.el9.x86_64                                             36/111
  Installing       : systemtap-client-5.4-4.el9.x86_64                                              37/111
  Installing       : sgml-common-0.6.3-58.el9.noarch                                                38/111
  Installing       : docbook-dtds-1.0-79.el9.noarch                                                 39/111
  Running scriptlet: docbook-dtds-1.0-79.el9.noarch                                                 39/111
  Installing       : docbook-style-xsl-1.79.2-16.el9.noarch                                         40/111
  Running scriptlet: docbook-style-xsl-1.79.2-16.el9.noarch                                         40/111
  Installing       : rust-srpm-macros-17-4.el9.noarch                                               41/111
  Installing       : qt5-srpm-macros-5.15.9-1.el9.noarch                                            42/111
  Installing       : perl-version-7:0.99.28-4.el9.x86_64                                            43/111
  Installing       : perl-srpm-macros-1-41.el9.noarch                                               44/111
  Installing       : perl-macros-4:5.32.1-483.el9.noarch                                            45/111
  Installing       : perl-lib-0.65-483.el9.x86_64                                                   46/111
  Installing       : perl-XML-Parser-2.46-10.el9.x86_64                                             47/111
  Installing       : perl-TermReadKey-2.38-11.el9.x86_64                                            48/111
  Installing       : perl-Fedora-VSP-0.001-23.el9.noarch                                            49/111
  Installing       : perl-Error-1:0.17029-7.el9.noarch                                              50/111
  Installing       : perl-Git-2.52.0-1.el9.noarch                                                   51/111
  Installing       : git-2.52.0-1.el9.x86_64                                                        52/111
  Installing       : openssl-devel-1:3.5.5-1.el9.x86_64                                             53/111
  Installing       : openblas-srpm-macros-2-11.el9.noarch                                           54/111
  Installing       : ocaml-srpm-macros-6-6.el9.noarch                                               55/111
  Installing       : nss-tools-3.112.0-8.el9.x86_64                                                 56/111
  Installing       : mkfontscale-1.2.1-3.el9.x86_64                                                 57/111
  Installing       : xorg-x11-fonts-ISO8859-1-100dpi-7.5-33.el9.noarch                              58/111
  Running scriptlet: xorg-x11-fonts-ISO8859-1-100dpi-7.5-33.el9.noarch                              58/111
  Installing       : lua-srpm-macros-1-6.el9.noarch                                                 59/111
  Installing       : lua-posix-35.0-8.el9.x86_64                                                    60/111
  Installing       : lua-5.4.4-4.el9.x86_64                                                         61/111
  Installing       : copy-jdk-configs-4.0-3.el9.noarch                                              62/111
  Installing       : libstdc++-devel-11.5.0-14.el9.x86_64                                           63/111
  Installing       : libipt-2.0.4-3.el9.x86_64                                                      64/111
  Installing       : libXaw-1.0.13-19.el9.x86_64                                                    65/111
  Installing       : graphviz-2.44.0-26.el9.x86_64                                                  66/111
  Running scriptlet: graphviz-2.44.0-26.el9.x86_64                                                  66/111
  Installing       : kernel-srpm-macros-1.0-14.el9.noarch                                           67/111
  Installing       : kernel-headers-5.14.0-694.el9.x86_64                                           68/111
  Installing       : glibc-headers-2.34-262.el9.x86_64                                              69/111
  Installing       : libxcrypt-devel-4.4.18-3.el9.x86_64                                            70/111
  Installing       : glibc-devel-2.34-262.el9.x86_64                                                71/111
  Installing       : gcc-11.5.0-14.el9.x86_64                                                       72/111
  Installing       : annobin-12.98-2.el9.x86_64                                                     73/111
  Installing       : gcc-plugin-annobin-11.5.0-14.el9.x86_64                                        74/111
  Installing       : kernel-devel-5.14.0-694.el9.x86_64                                             75/111
  Running scriptlet: kernel-devel-5.14.0-694.el9.x86_64                                             75/111
  Installing       : systemtap-devel-5.4-4.el9.x86_64                                               76/111
  Installing       : ghc-srpm-macros-1.5.0-6.el9.noarch                                             77/111
  Installing       : gettext-common-devel-0.21-8.el9.noarch                                         78/111
  Installing       : gettext-devel-0.21-8.el9.x86_64                                                79/111
  Installing       : efi-srpm-macros-6-4.el9.noarch                                                 80/111
  Installing       : boost-regex-1.75.0-13.el9.x86_64                                               81/111
  Installing       : source-highlight-3.1.9-12.el9.x86_64                                           82/111
  Installing       : gdb-headless-16.3-3.el9.x86_64                                                 83/111
  Installing       : debugedit-5.0-11.el9.x86_64                                                    84/111
  Installing       : gdb-16.3-3.el9.x86_64                                                          85/111
  Installing       : valgrind-1:3.26.0-5.el9.x86_64                                                 86/111
  Installing       : valgrind-gdb-1:3.26.0-5.el9.x86_64                                             87/111
  Installing       : valgrind-scripts-1:3.26.0-5.el9.x86_64                                         88/111
  Installing       : zstd-1.5.5-1.el9.x86_64                                                        89/111
  Installing       : fonts-srpm-macros-1:2.0.5-7.el9.1.noarch                                       90/111
  Installing       : go-srpm-macros-3.8.1-1.el9.noarch                                              91/111
  Installing       : python-srpm-macros-3.9-54.el9.noarch                                           92/111
  Installing       : redhat-rpm-config-210-1.el9.noarch                                             93/111
  Running scriptlet: redhat-rpm-config-210-1.el9.noarch                                             93/111
  Installing       : rpm-build-4.16.1.3-40.el9.x86_64                                               94/111
  Installing       : pyproject-srpm-macros-1.18.5-1.el9.noarch                                      95/111
  Installing       : lksctp-tools-1.0.19-2.el9.x86_64                                               96/111
  Installing       : java-1.8.0-openjdk-headless-1:1.8.0.482.b08-3.el9.x86_64                       97/111
  Running scriptlet: java-1.8.0-openjdk-headless-1:1.8.0.482.b08-3.el9.x86_64                       97/111
  Installing       : jna-5.6.0-8.el9.x86_64                                                         98/111
  Installing       : valgrind-devel-1:3.26.0-5.el9.x86_64                                           99/111
  Installing       : asciidoc-9.1.0-3.el9.noarch                                                   100/111
  Installing       : intltool-0.51.0-20.el9.noarch                                                 101/111
  Installing       : systemtap-5.4-4.el9.x86_64                                                    102/111
  Running scriptlet: systemtap-5.4-4.el9.x86_64                                                    102/111
  Installing       : gcc-c++-11.5.0-14.el9.x86_64                                                  103/111
  Installing       : libtool-2.4.6-46.el9.x86_64                                                   104/111
  Running scriptlet: pesign-115-6.el9.x86_64                                                       105/111
  Installing       : pesign-115-6.el9.x86_64                                                       105/111
  Running scriptlet: pesign-115-6.el9.x86_64                                                       105/111
  Installing       : perl-generators-1.13-1.el9.noarch                                             106/111
  Installing       : patchutils-0.4.2-7.el9.x86_64                                                 107/111
  Installing       : ltrace-0.7.91-43.el9.x86_64                                                   108/111
  Installing       : diffstat-1.64-6.el9.x86_64                                                    109/111
  Installing       : byacc-2.0.20210109-4.el9.x86_64                                               110/111
  Installing       : rpm-sign-4.16.1.3-40.el9.x86_64                                               111/111
  Running scriptlet: copy-jdk-configs-4.0-3.el9.noarch                                             111/111
  Running scriptlet: java-1.8.0-openjdk-headless-1:1.8.0.482.b08-3.el9.x86_64                      111/111
  Running scriptlet: pesign-115-6.el9.x86_64                                                       111/111
  Running scriptlet: rpm-sign-4.16.1.3-40.el9.x86_64                                               111/111
  Verifying        : efivar-libs-38-3.el9.x86_64                                                     1/111
  Verifying        : elfutils-0.194-1.el9.x86_64                                                     2/111
  Verifying        : lksctp-tools-1.0.19-2.el9.x86_64                                                3/111
  Verifying        : make-1:4.3-8.el9.x86_64                                                         4/111
  Verifying        : mokutil-2:0.7.2-4.el9.x86_64                                                    5/111
  Verifying        : rpm-sign-4.16.1.3-40.el9.x86_64                                                 6/111
  Verifying        : zstd-1.5.5-1.el9.x86_64                                                         7/111
  Verifying        : adwaita-gtk2-theme-3.28-14.el9.x86_64                                           8/111
  Verifying        : annobin-12.98-2.el9.x86_64                                                      9/111
  Verifying        : asciidoc-9.1.0-3.el9.noarch                                                    10/111
  Verifying        : autoconf-2.69-41.el9.noarch                                                    11/111
  Verifying        : automake-1.16.2-8.el9.noarch                                                   12/111
  Verifying        : bison-3.7.4-5.el9.x86_64                                                       13/111
  Verifying        : boost-filesystem-1.75.0-13.el9.x86_64                                          14/111
  Verifying        : boost-regex-1.75.0-13.el9.x86_64                                               15/111
  Verifying        : boost-system-1.75.0-13.el9.x86_64                                              16/111
  Verifying        : boost-thread-1.75.0-13.el9.x86_64                                              17/111
  Verifying        : byacc-2.0.20210109-4.el9.x86_64                                                18/111
  Verifying        : copy-jdk-configs-4.0-3.el9.noarch                                              19/111
  Verifying        : debugedit-5.0-11.el9.x86_64                                                    20/111
  Verifying        : diffstat-1.64-6.el9.x86_64                                                     21/111
  Verifying        : docbook-dtds-1.0-79.el9.noarch                                                 22/111
  Verifying        : docbook-style-xsl-1.79.2-16.el9.noarch                                         23/111
  Verifying        : dwz-0.16-1.el9.x86_64                                                          24/111
  Verifying        : dyninst-13.0.0-1.el9.x86_64                                                    25/111
  Verifying        : efi-srpm-macros-6-4.el9.noarch                                                 26/111
  Verifying        : elfutils-devel-0.194-1.el9.x86_64                                              27/111
  Verifying        : elfutils-libelf-devel-0.194-1.el9.x86_64                                       28/111
  Verifying        : flex-2.6.4-9.el9.x86_64                                                        29/111
  Verifying        : fonts-srpm-macros-1:2.0.5-7.el9.1.noarch                                       30/111
  Verifying        : gcc-11.5.0-14.el9.x86_64                                                       31/111
  Verifying        : gcc-c++-11.5.0-14.el9.x86_64                                                   32/111
  Verifying        : gcc-plugin-annobin-11.5.0-14.el9.x86_64                                        33/111
  Verifying        : gdb-16.3-3.el9.x86_64                                                          34/111
  Verifying        : gdb-headless-16.3-3.el9.x86_64                                                 35/111
  Verifying        : gettext-common-devel-0.21-8.el9.noarch                                         36/111
  Verifying        : gettext-devel-0.21-8.el9.x86_64                                                37/111
  Verifying        : ghc-srpm-macros-1.5.0-6.el9.noarch                                             38/111
  Verifying        : git-2.52.0-1.el9.x86_64                                                        39/111
  Verifying        : git-core-2.52.0-1.el9.x86_64                                                   40/111
  Verifying        : git-core-doc-2.52.0-1.el9.noarch                                               41/111
  Verifying        : glibc-devel-2.34-262.el9.x86_64                                                42/111
  Verifying        : glibc-headers-2.34-262.el9.x86_64                                              43/111
  Verifying        : go-srpm-macros-3.8.1-1.el9.noarch                                              44/111
  Verifying        : graphviz-2.44.0-26.el9.x86_64                                                  45/111
  Verifying        : gtk2-2.24.33-8.el9.x86_64                                                      46/111
  Verifying        : ibus-gtk2-1.5.25-6.el9.x86_64                                                  47/111
  Verifying        : intltool-0.51.0-20.el9.noarch                                                  48/111
  Verifying        : java-1.8.0-openjdk-headless-1:1.8.0.482.b08-3.el9.x86_64                       49/111
  Verifying        : javapackages-filesystem-6.4.0-1.el9.noarch                                     50/111
  Verifying        : jna-5.6.0-8.el9.x86_64                                                         51/111
  Verifying        : kernel-devel-5.14.0-694.el9.x86_64                                             52/111
  Verifying        : kernel-headers-5.14.0-694.el9.x86_64                                           53/111
  Verifying        : kernel-srpm-macros-1.0-14.el9.noarch                                           54/111
  Verifying        : libXaw-1.0.13-19.el9.x86_64                                                    55/111
  Verifying        : libcanberra-gtk2-0.30-27.el9.x86_64                                            56/111
  Verifying        : libipt-2.0.4-3.el9.x86_64                                                      57/111
  Verifying        : libstdc++-devel-11.5.0-14.el9.x86_64                                           58/111
  Verifying        : libtool-2.4.6-46.el9.x86_64                                                    59/111
  Verifying        : libxcrypt-devel-4.4.18-3.el9.x86_64                                            60/111
  Verifying        : libzstd-devel-1.5.5-1.el9.x86_64                                               61/111
  Verifying        : ltrace-0.7.91-43.el9.x86_64                                                    62/111
  Verifying        : lua-5.4.4-4.el9.x86_64                                                         63/111
  Verifying        : lua-posix-35.0-8.el9.x86_64                                                    64/111
  Verifying        : lua-srpm-macros-1-6.el9.noarch                                                 65/111
  Verifying        : m4-1.4.19-1.el9.x86_64                                                         66/111
  Verifying        : mkfontscale-1.2.1-3.el9.x86_64                                                 67/111
  Verifying        : nss-tools-3.112.0-8.el9.x86_64                                                 68/111
  Verifying        : ocaml-srpm-macros-6-6.el9.noarch                                               69/111
  Verifying        : openblas-srpm-macros-2-11.el9.noarch                                           70/111
  Verifying        : openssl-devel-1:3.5.5-1.el9.x86_64                                             71/111
  Verifying        : patch-2.7.6-16.el9.x86_64                                                      72/111
  Verifying        : patchutils-0.4.2-7.el9.x86_64                                                  73/111
  Verifying        : perl-Error-1:0.17029-7.el9.noarch                                              74/111
  Verifying        : perl-Fedora-VSP-0.001-23.el9.noarch                                            75/111
  Verifying        : perl-File-Compare-1.100.600-483.el9.noarch                                     76/111
  Verifying        : perl-File-Copy-2.34-483.el9.noarch                                             77/111
  Verifying        : perl-Git-2.52.0-1.el9.noarch                                                   78/111
  Verifying        : perl-TermReadKey-2.38-11.el9.x86_64                                            79/111
  Verifying        : perl-Thread-Queue-3.14-460.el9.noarch                                          80/111
  Verifying        : perl-XML-Parser-2.46-10.el9.x86_64                                             81/111
  Verifying        : perl-generators-1.13-1.el9.noarch                                              82/111
  Verifying        : perl-lib-0.65-483.el9.x86_64                                                   83/111
  Verifying        : perl-macros-4:5.32.1-483.el9.noarch                                            84/111
  Verifying        : perl-srpm-macros-1-41.el9.noarch                                               85/111
  Verifying        : perl-threads-1:2.25-460.el9.x86_64                                             86/111
  Verifying        : perl-threads-shared-1.61-460.el9.x86_64                                        87/111
  Verifying        : perl-version-7:0.99.28-4.el9.x86_64                                            88/111
  Verifying        : pesign-115-6.el9.x86_64                                                        89/111
  Verifying        : pyproject-srpm-macros-1.18.5-1.el9.noarch                                      90/111
  Verifying        : python-srpm-macros-3.9-54.el9.noarch                                           91/111
  Verifying        : qt5-srpm-macros-5.15.9-1.el9.noarch                                            92/111
  Verifying        : redhat-rpm-config-210-1.el9.noarch                                             93/111
  Verifying        : rpm-build-4.16.1.3-40.el9.x86_64                                               94/111
  Verifying        : rust-srpm-macros-17-4.el9.noarch                                               95/111
  Verifying        : sgml-common-0.6.3-58.el9.noarch                                                96/111
  Verifying        : source-highlight-3.1.9-12.el9.x86_64                                           97/111
  Verifying        : systemtap-5.4-4.el9.x86_64                                                     98/111
  Verifying        : systemtap-client-5.4-4.el9.x86_64                                              99/111
  Verifying        : systemtap-devel-5.4-4.el9.x86_64                                              100/111
  Verifying        : systemtap-runtime-5.4-4.el9.x86_64                                            101/111
  Verifying        : tbb-2020.3-9.el9.x86_64                                                       102/111
  Verifying        : tzdata-java-2026a-1.el9.noarch                                                103/111
  Verifying        : valgrind-1:3.26.0-5.el9.x86_64                                                104/111
  Verifying        : valgrind-devel-1:3.26.0-5.el9.x86_64                                          105/111
  Verifying        : valgrind-docs-1:3.26.0-5.el9.x86_64                                           106/111
  Verifying        : valgrind-gdb-1:3.26.0-5.el9.x86_64                                            107/111
  Verifying        : valgrind-scripts-1:3.26.0-5.el9.x86_64                                        108/111
  Verifying        : xorg-x11-fonts-ISO8859-1-100dpi-7.5-33.el9.noarch                             109/111
  Verifying        : xz-devel-5.2.5-8.el9.x86_64                                                   110/111
  Verifying        : zlib-devel-1.2.11-41.el9.x86_64                                               111/111

Installed:
  adwaita-gtk2-theme-3.28-14.el9.x86_64         annobin-12.98-2.el9.x86_64
  asciidoc-9.1.0-3.el9.noarch                   autoconf-2.69-41.el9.noarch
  automake-1.16.2-8.el9.noarch                  bison-3.7.4-5.el9.x86_64
  boost-filesystem-1.75.0-13.el9.x86_64         boost-regex-1.75.0-13.el9.x86_64
  boost-system-1.75.0-13.el9.x86_64             boost-thread-1.75.0-13.el9.x86_64
  byacc-2.0.20210109-4.el9.x86_64               copy-jdk-configs-4.0-3.el9.noarch
  debugedit-5.0-11.el9.x86_64                   diffstat-1.64-6.el9.x86_64
  docbook-dtds-1.0-79.el9.noarch                docbook-style-xsl-1.79.2-16.el9.noarch
  dwz-0.16-1.el9.x86_64                         dyninst-13.0.0-1.el9.x86_64
  efi-srpm-macros-6-4.el9.noarch                efivar-libs-38-3.el9.x86_64
  elfutils-0.194-1.el9.x86_64                   elfutils-devel-0.194-1.el9.x86_64
  elfutils-libelf-devel-0.194-1.el9.x86_64      flex-2.6.4-9.el9.x86_64
  fonts-srpm-macros-1:2.0.5-7.el9.1.noarch      gcc-11.5.0-14.el9.x86_64
  gcc-c++-11.5.0-14.el9.x86_64                  gcc-plugin-annobin-11.5.0-14.el9.x86_64
  gdb-16.3-3.el9.x86_64                         gdb-headless-16.3-3.el9.x86_64
  gettext-common-devel-0.21-8.el9.noarch        gettext-devel-0.21-8.el9.x86_64
  ghc-srpm-macros-1.5.0-6.el9.noarch            git-2.52.0-1.el9.x86_64
  git-core-2.52.0-1.el9.x86_64                  git-core-doc-2.52.0-1.el9.noarch
  glibc-devel-2.34-262.el9.x86_64               glibc-headers-2.34-262.el9.x86_64
  go-srpm-macros-3.8.1-1.el9.noarch             graphviz-2.44.0-26.el9.x86_64
  gtk2-2.24.33-8.el9.x86_64                     ibus-gtk2-1.5.25-6.el9.x86_64
  intltool-0.51.0-20.el9.noarch                 java-1.8.0-openjdk-headless-1:1.8.0.482.b08-3.el9.x86_64
  javapackages-filesystem-6.4.0-1.el9.noarch    jna-5.6.0-8.el9.x86_64
  kernel-devel-5.14.0-694.el9.x86_64            kernel-headers-5.14.0-694.el9.x86_64
  kernel-srpm-macros-1.0-14.el9.noarch          libXaw-1.0.13-19.el9.x86_64
  libcanberra-gtk2-0.30-27.el9.x86_64           libipt-2.0.4-3.el9.x86_64
  libstdc++-devel-11.5.0-14.el9.x86_64          libtool-2.4.6-46.el9.x86_64
  libxcrypt-devel-4.4.18-3.el9.x86_64           libzstd-devel-1.5.5-1.el9.x86_64
  lksctp-tools-1.0.19-2.el9.x86_64              ltrace-0.7.91-43.el9.x86_64
  lua-5.4.4-4.el9.x86_64                        lua-posix-35.0-8.el9.x86_64
  lua-srpm-macros-1-6.el9.noarch                m4-1.4.19-1.el9.x86_64
  make-1:4.3-8.el9.x86_64                       mkfontscale-1.2.1-3.el9.x86_64
  mokutil-2:0.7.2-4.el9.x86_64                  nss-tools-3.112.0-8.el9.x86_64
  ocaml-srpm-macros-6-6.el9.noarch              openblas-srpm-macros-2-11.el9.noarch
  openssl-devel-1:3.5.5-1.el9.x86_64            patch-2.7.6-16.el9.x86_64
  patchutils-0.4.2-7.el9.x86_64                 perl-Error-1:0.17029-7.el9.noarch
  perl-Fedora-VSP-0.001-23.el9.noarch           perl-File-Compare-1.100.600-483.el9.noarch
  perl-File-Copy-2.34-483.el9.noarch            perl-Git-2.52.0-1.el9.noarch
  perl-TermReadKey-2.38-11.el9.x86_64           perl-Thread-Queue-3.14-460.el9.noarch
  perl-XML-Parser-2.46-10.el9.x86_64            perl-generators-1.13-1.el9.noarch
  perl-lib-0.65-483.el9.x86_64                  perl-macros-4:5.32.1-483.el9.noarch
  perl-srpm-macros-1-41.el9.noarch              perl-threads-1:2.25-460.el9.x86_64
  perl-threads-shared-1.61-460.el9.x86_64       perl-version-7:0.99.28-4.el9.x86_64
  pesign-115-6.el9.x86_64                       pyproject-srpm-macros-1.18.5-1.el9.noarch
  python-srpm-macros-3.9-54.el9.noarch          qt5-srpm-macros-5.15.9-1.el9.noarch
  redhat-rpm-config-210-1.el9.noarch            rpm-build-4.16.1.3-40.el9.x86_64
  rpm-sign-4.16.1.3-40.el9.x86_64               rust-srpm-macros-17-4.el9.noarch
  sgml-common-0.6.3-58.el9.noarch               source-highlight-3.1.9-12.el9.x86_64
  systemtap-5.4-4.el9.x86_64                    systemtap-client-5.4-4.el9.x86_64
  systemtap-devel-5.4-4.el9.x86_64              systemtap-runtime-5.4-4.el9.x86_64
  tbb-2020.3-9.el9.x86_64                       tzdata-java-2026a-1.el9.noarch
  valgrind-1:3.26.0-5.el9.x86_64                valgrind-devel-1:3.26.0-5.el9.x86_64
  valgrind-docs-1:3.26.0-5.el9.x86_64           valgrind-gdb-1:3.26.0-5.el9.x86_64
  valgrind-scripts-1:3.26.0-5.el9.x86_64        xorg-x11-fonts-ISO8859-1-100dpi-7.5-33.el9.noarch
  xz-devel-5.2.5-8.el9.x86_64                   zlib-devel-1.2.11-41.el9.x86_64
  zstd-1.5.5-1.el9.x86_64

Complete!

[astraadm@192 ~]$ sudo dnf install rpm-build rpm-devel rpmlint make gcc gcc-c++
[sudo] password for astraadm:
Sorry, try again.
[sudo] password for astraadm:
Last metadata expiration check: 0:08:17 ago on Sun 26 Apr 2026 08:03:08 PM MSK.
Package rpm-build-4.16.1.3-40.el9.x86_64 is already installed.
Package make-1:4.3-8.el9.x86_64 is already installed.
Package gcc-11.5.0-14.el9.x86_64 is already installed.
Package gcc-c++-11.5.0-14.el9.x86_64 is already installed.
Dependencies resolved.
===========================================================================================================
 Package                     Architecture       Version                        Repository             Size
===========================================================================================================
Installing:
 rpm-devel                   x86_64             4.16.1.3-40.el9                appstream              85 k
 rpmlint                     noarch             1.11-19.el9                    appstream             198 k
Installing dependencies:
 enchant                     x86_64             1:1.6.0-30.el9                 appstream              62 k
 popt-devel                  x86_64             1.18-8.el9                     appstream              26 k
 python3-enchant             noarch             3.2.0-5.el9                    appstream              86 k

Transaction Summary
===========================================================================================================
Install  5 Packages

Total download size: 456 k
Installed size: 1.4 M
Is this ok [y/N]: y
Downloading Packages:
[MIRROR] enchant-1.6.0-30.el9.x86_64.rpm: Curl error (28): Timeout was reached for http://ftp.nsc.ru/pub/centos-9/9-stream/AppStream/x86_64/os/Packages/enchant-1.6.0-30.el9.x86_64.rpm [Failed to connect to ftp.nsc.ru port 80: Connection timed out]
[MIRROR] popt-devel-1.18-8.el9.x86_64.rpm: Curl error (28): Timeout was reached for http://ftp.nsc.ru/pub/centos-9/9-stream/AppStream/x86_64/os/Packages/popt-devel-1.18-8.el9.x86_64.rpm [Failed to connect to ftp.nsc.ru port 80: Connection timed out]
[MIRROR] python3-enchant-3.2.0-5.el9.noarch.rpm: Curl error (28): Timeout was reached for http://ftp.nsc.ru/pub/centos-9/9-stream/AppStream/x86_64/os/Packages/python3-enchant-3.2.0-5.el9.noarch.rpm [Failed to connect to ftp.nsc.ru port 80: Connection timed out]
[MIRROR] enchant-1.6.0-30.el9.x86_64.rpm: Curl error (28): Timeout was reached for https://mirrors.chroot.ro/centos-stream/9-stream/AppStream/x86_64/os/Packages/enchant-1.6.0-30.el9.x86_64.rpm [Failed to connect to mirrors.chroot.ro port 443: Connection timed out]
[MIRROR] popt-devel-1.18-8.el9.x86_64.rpm: Curl error (28): Timeout was reached for https://mirrors.chroot.ro/centos-stream/9-stream/AppStream/x86_64/os/Packages/popt-devel-1.18-8.el9.x86_64.rpm [Failed to connect to mirrors.chroot.ro port 443: Connection timed out]
[MIRROR] python3-enchant-3.2.0-5.el9.noarch.rpm: Curl error (28): Timeout was reached for https://mirrors.chroot.ro/centos-stream/9-stream/AppStream/x86_64/os/Packages/python3-enchant-3.2.0-5.el9.noarch.rpm [Failed to connect to mirrors.chroot.ro port 443: Connection timed out]
[MIRROR] enchant-1.6.0-30.el9.x86_64.rpm: Curl error (28): Timeout was reached for http://ftp.nsc.ru/pub/centos-9/9-stream/AppStream/x86_64/os/Packages/enchant-1.6.0-30.el9.x86_64.rpm [Failed to connect to ftp.nsc.ru port 80: Connection timed out]
(1/5): enchant-1.6.0-30.el9.x86_64.rpm                                     1.2 kB/s |  62 kB     00:51
(2/5): rpm-devel-4.16.1.3-40.el9.x86_64.rpm                                172 kB/s |  85 kB     00:00
(3/5): rpmlint-1.11-19.el9.noarch.rpm                                      277 kB/s | 198 kB     00:00
[MIRROR] popt-devel-1.18-8.el9.x86_64.rpm: Curl error (28): Timeout was reached for https://ftp.nsc.ru/pub/centos-9/9-stream/AppStream/x86_64/os/Packages/popt-devel-1.18-8.el9.x86_64.rpm [Operation too slow. Less than 1000 bytes/sec transferred the last 30 seconds]
[MIRROR] python3-enchant-3.2.0-5.el9.noarch.rpm: Curl error (28): Timeout was reached for https://ftp.nsc.ru/pub/centos-9/9-stream/AppStream/x86_64/os/Packages/python3-enchant-3.2.0-5.el9.noarch.rpm [Operation too slow. Less than 1000 bytes/sec transferred the last 30 seconds]
(4/5): popt-devel-1.18-8.el9.x86_64.rpm                                    325  B/s |  26 kB     01:21
[MIRROR] python3-enchant-3.2.0-5.el9.noarch.rpm: Curl error (28): Timeout was reached for http://mirror.unix-solutions.be/centosstream/9-stream/AppStream/x86_64/os/Packages/python3-enchant-3.2.0-5.el9.noarch.rpm [Failed to connect to mirror.unix-solutions.be port 80: Connection timed out]
[MIRROR] python3-enchant-3.2.0-5.el9.noarch.rpm: Curl error (28): Timeout was reached for https://mirror.unix-solutions.be/centosstream/9-stream/AppStream/x86_64/os/Packages/python3-enchant-3.2.0-5.el9.noarch.rpm [Failed to connect to mirror.unix-solutions.be port 443: Connection timed out]
[MIRROR] python3-enchant-3.2.0-5.el9.noarch.rpm: Curl error (7): Couldn't connect to server for http://mirrors.xtom.de/centos-stream/9-stream/AppStream/x86_64/os/Packages/python3-enchant-3.2.0-5.el9.noarch.rpm [Failed to connect to mirrors.xtom.de port 80: Connection reset by peer]
(5/5): python3-enchant-3.2.0-5.el9.noarch.rpm                              674  B/s |  86 kB     02:10
-----------------------------------------------------------------------------------------------------------
Total                                                                      3.5 kB/s | 456 kB     02:11
Running transaction check
Transaction check succeeded.
Running transaction test
Transaction test succeeded.
Running transaction
  Preparing        :                                                                                   1/1
  Installing       : popt-devel-1.18-8.el9.x86_64                                                      1/5
  Installing       : enchant-1:1.6.0-30.el9.x86_64                                                     2/5
  Installing       : python3-enchant-3.2.0-5.el9.noarch                                                3/5
  Installing       : rpmlint-1.11-19.el9.noarch                                                        4/5
  Installing       : rpm-devel-4.16.1.3-40.el9.x86_64                                                  5/5
  Running scriptlet: rpm-devel-4.16.1.3-40.el9.x86_64                                                  5/5
  Verifying        : enchant-1:1.6.0-30.el9.x86_64                                                     1/5
  Verifying        : popt-devel-1.18-8.el9.x86_64                                                      2/5
  Verifying        : python3-enchant-3.2.0-5.el9.noarch                                                3/5
  Verifying        : rpm-devel-4.16.1.3-40.el9.x86_64                                                  4/5
  Verifying        : rpmlint-1.11-19.el9.noarch                                                        5/5

Installed:
  enchant-1:1.6.0-30.el9.x86_64       popt-devel-1.18-8.el9.x86_64    python3-enchant-3.2.0-5.el9.noarch
  rpm-devel-4.16.1.3-40.el9.x86_64    rpmlint-1.11-19.el9.noarch

Complete!

[astraadm@192 ~]$ sudo dnf install pcre-devel openssl-devel apr-devel apr-util-devel libxml2-devel
Last metadata expiration check: 0:14:26 ago on Sun 26 Apr 2026 08:03:08 PM MSK.
Package openssl-devel-1:3.5.5-1.el9.x86_64 is already installed.
Dependencies resolved.
===========================================================================================================
 Package                       Architecture        Version                    Repository              Size
===========================================================================================================
Installing:
 apr-devel                     x86_64              1.7.0-12.el9               appstream              229 k
 apr-util-devel                x86_64              1.6.1-23.el9               appstream               75 k
 libxml2-devel                 x86_64              2.9.13-14.el9              appstream              899 k
 pcre-devel                    x86_64              8.44-4.el9                 appstream              506 k
Installing dependencies:
 apr                           x86_64              1.7.0-12.el9               appstream              123 k
 apr-util                      x86_64              1.6.1-23.el9               appstream               95 k
 apr-util-bdb                  x86_64              1.6.1-23.el9               appstream               13 k
 cmake-filesystem              x86_64              3.31.8-3.el9               appstream               19 k
 cyrus-sasl                    x86_64              2.1.27-21.el9              baseos                  73 k
 cyrus-sasl-devel              x86_64              2.1.27-21.el9              appstream              113 k
 expat-devel                   x86_64              2.5.0-6.el9                appstream               52 k
 libdb-devel                   x86_64              5.3.28-57.el9              appstream               37 k
 openldap-devel                x86_64              2.6.8-4.el9                appstream              746 k
 pcre-cpp                      x86_64              8.44-4.el9                 appstream               26 k
 pcre-utf16                    x86_64              8.44-4.el9                 appstream              184 k
 pcre-utf32                    x86_64              8.44-4.el9                 appstream              174 k
Installing weak dependencies:
 apr-util-openssl              x86_64              1.6.1-23.el9               appstream               15 k

Transaction Summary
===========================================================================================================
Install  17 Packages

Total download size: 3.3 M
Installed size: 18 M
Is this ok [y/N]: y
Downloading Packages:
(1/17): cyrus-sasl-2.1.27-21.el9.x86_64.rpm                                118 kB/s |  73 kB     00:00
(2/17): apr-1.7.0-12.el9.x86_64.rpm                                        110 kB/s | 123 kB     00:01
(3/17): apr-util-bdb-1.6.1-23.el9.x86_64.rpm                               105 kB/s |  13 kB     00:00
(4/17): apr-devel-1.7.0-12.el9.x86_64.rpm                                  150 kB/s | 229 kB     00:01
(5/17): apr-util-devel-1.6.1-23.el9.x86_64.rpm                             262 kB/s |  75 kB     00:00
(6/17): apr-util-openssl-1.6.1-23.el9.x86_64.rpm                           150 kB/s |  15 kB     00:00
(7/17): apr-util-1.6.1-23.el9.x86_64.rpm                                    87 kB/s |  95 kB     00:01
(8/17): cmake-filesystem-3.31.8-3.el9.x86_64.rpm                            84 kB/s |  19 kB     00:00
(9/17): libdb-devel-5.3.28-57.el9.x86_64.rpm                               109 kB/s |  37 kB     00:00
(10/17): expat-devel-2.5.0-6.el9.x86_64.rpm                                115 kB/s |  52 kB     00:00
(11/17): cyrus-sasl-devel-2.1.27-21.el9.x86_64.rpm                         104 kB/s | 113 kB     00:01
(12/17): pcre-cpp-8.44-4.el9.x86_64.rpm                                    158 kB/s |  26 kB     00:00
(13/17): libxml2-devel-2.9.13-14.el9.x86_64.rpm                            576 kB/s | 899 kB     00:01
(14/17): pcre-devel-8.44-4.el9.x86_64.rpm                                  502 kB/s | 506 kB     00:01
(15/17): openldap-devel-2.6.8-4.el9.x86_64.rpm                             423 kB/s | 746 kB     00:01
(16/17): pcre-utf16-8.44-4.el9.x86_64.rpm                                  580 kB/s | 184 kB     00:00
(17/17): pcre-utf32-8.44-4.el9.x86_64.rpm                                  583 kB/s | 174 kB     00:00
-----------------------------------------------------------------------------------------------------------
Total                                                                      319 kB/s | 3.3 MB     00:10
Running transaction check
Transaction check succeeded.
Running transaction test
Transaction test succeeded.
Running transaction
  Preparing        :                                                                                   1/1
  Installing       : apr-1.7.0-12.el9.x86_64                                                          1/17
  Installing       : apr-util-bdb-1.6.1-23.el9.x86_64                                                 2/17
  Installing       : apr-util-openssl-1.6.1-23.el9.x86_64                                             3/17
  Installing       : apr-util-1.6.1-23.el9.x86_64                                                     4/17
  Installing       : apr-devel-1.7.0-12.el9.x86_64                                                    5/17
  Installing       : pcre-utf32-8.44-4.el9.x86_64                                                     6/17
  Installing       : pcre-utf16-8.44-4.el9.x86_64                                                     7/17
  Installing       : pcre-cpp-8.44-4.el9.x86_64                                                       8/17
  Installing       : libdb-devel-5.3.28-57.el9.x86_64                                                 9/17
  Installing       : expat-devel-2.5.0-6.el9.x86_64                                                  10/17
  Installing       : cmake-filesystem-3.31.8-3.el9.x86_64                                            11/17
  Running scriptlet: cyrus-sasl-2.1.27-21.el9.x86_64                                                 12/17
  Installing       : cyrus-sasl-2.1.27-21.el9.x86_64                                                 12/17
  Running scriptlet: cyrus-sasl-2.1.27-21.el9.x86_64                                                 12/17
  Installing       : cyrus-sasl-devel-2.1.27-21.el9.x86_64                                           13/17
  Installing       : openldap-devel-2.6.8-4.el9.x86_64                                               14/17
  Installing       : apr-util-devel-1.6.1-23.el9.x86_64                                              15/17
  Installing       : libxml2-devel-2.9.13-14.el9.x86_64                                              16/17
  Installing       : pcre-devel-8.44-4.el9.x86_64                                                    17/17
  Running scriptlet: pcre-devel-8.44-4.el9.x86_64                                                    17/17
  Verifying        : cyrus-sasl-2.1.27-21.el9.x86_64                                                  1/17
  Verifying        : apr-1.7.0-12.el9.x86_64                                                          2/17
  Verifying        : apr-devel-1.7.0-12.el9.x86_64                                                    3/17
  Verifying        : apr-util-1.6.1-23.el9.x86_64                                                     4/17
  Verifying        : apr-util-bdb-1.6.1-23.el9.x86_64                                                 5/17
  Verifying        : apr-util-devel-1.6.1-23.el9.x86_64                                               6/17
  Verifying        : apr-util-openssl-1.6.1-23.el9.x86_64                                             7/17
  Verifying        : cmake-filesystem-3.31.8-3.el9.x86_64                                             8/17
  Verifying        : cyrus-sasl-devel-2.1.27-21.el9.x86_64                                            9/17
  Verifying        : expat-devel-2.5.0-6.el9.x86_64                                                  10/17
  Verifying        : libdb-devel-5.3.28-57.el9.x86_64                                                11/17
  Verifying        : libxml2-devel-2.9.13-14.el9.x86_64                                              12/17
  Verifying        : openldap-devel-2.6.8-4.el9.x86_64                                               13/17
  Verifying        : pcre-cpp-8.44-4.el9.x86_64                                                      14/17
  Verifying        : pcre-devel-8.44-4.el9.x86_64                                                    15/17
  Verifying        : pcre-utf16-8.44-4.el9.x86_64                                                    16/17
  Verifying        : pcre-utf32-8.44-4.el9.x86_64                                                    17/17

Installed:
  apr-1.7.0-12.el9.x86_64                              apr-devel-1.7.0-12.el9.x86_64
  apr-util-1.6.1-23.el9.x86_64                         apr-util-bdb-1.6.1-23.el9.x86_64
  apr-util-devel-1.6.1-23.el9.x86_64                   apr-util-openssl-1.6.1-23.el9.x86_64
  cmake-filesystem-3.31.8-3.el9.x86_64                 cyrus-sasl-2.1.27-21.el9.x86_64
  cyrus-sasl-devel-2.1.27-21.el9.x86_64                expat-devel-2.5.0-6.el9.x86_64
  libdb-devel-5.3.28-57.el9.x86_64                     libxml2-devel-2.9.13-14.el9.x86_64
  openldap-devel-2.6.8-4.el9.x86_64                    pcre-cpp-8.44-4.el9.x86_64
  pcre-devel-8.44-4.el9.x86_64                         pcre-utf16-8.44-4.el9.x86_64
  pcre-utf32-8.44-4.el9.x86_64

Complete!
[root@192 ~]# dnf config-manager --set-enabled crb
[root@192 ~]# sudo dnf install lua-devel
CentOS Stream 9 - BaseOS                                                   520  B/s |  15 kB     00:29
CentOS Stream 9 - AppStream                                                 18 kB/s |  15 kB     00:00
CentOS Stream 9 - CRB                                                      1.1 MB/s | 8.0 MB     00:07
Dependencies resolved.
===========================================================================================================
 Package                      Architecture         Version                   Repository               Size
===========================================================================================================
Installing:
 lua-devel                    x86_64               5.4.4-4.el9               crb                      22 k
Installing dependencies:
 lua-rpm-macros               noarch               1-6.el9                   appstream                10 k

Transaction Summary
===========================================================================================================
Install  2 Packages

Total download size: 32 k
Installed size: 50 k
Is this ok [y/N]: y
Downloading Packages:
(1/2): lua-rpm-macros-1-6.el9.noarch.rpm                                    48 kB/s |  10 kB     00:00
(2/2): lua-devel-5.4.4-4.el9.x86_64.rpm                                     31 kB/s |  22 kB     00:00
-----------------------------------------------------------------------------------------------------------
Total                                                                      2.7 kB/s |  32 kB     00:12
Running transaction check
Transaction check succeeded.
Running transaction test
Transaction test succeeded.
Running transaction
  Preparing        :                                                                                   1/1
  Installing       : lua-rpm-macros-1-6.el9.noarch                                                     1/2
  Installing       : lua-devel-5.4.4-4.el9.x86_64                                                      2/2
  Running scriptlet: lua-devel-5.4.4-4.el9.x86_64                                                      2/2
  Verifying        : lua-rpm-macros-1-6.el9.noarch                                                     1/2
  Verifying        : lua-devel-5.4.4-4.el9.x86_64                                                      2/2

Installed:
  lua-devel-5.4.4-4.el9.x86_64                        lua-rpm-macros-1-6.el9.noarch

Complete!
