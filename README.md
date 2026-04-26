# 1. Подготовка системы и установка инструментов
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
# 2. Создание структуры директорий
[root@192 ~]# mkdir -p ~/rpmbuild/{BUILD,RPMS,SOURCES,SPECS,SRPMS}
# 3. Скачивание исходников Apache
[root@192 ~]# cd ~/rpmbuild/SOURCES
[root@192 SOURCES]# wget https://archive.apache.org/dist/httpd/httpd-2.4.62.tar.bz2
--2026-04-26 20:35:51--  https://archive.apache.org/dist/httpd/httpd-2.4.62.tar.bz2
Resolving archive.apache.org (archive.apache.org)... 65.108.204.189, 2a01:4f9:1a:a084::2
Connecting to archive.apache.org (archive.apache.org)|65.108.204.189|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 7521661 (7.2M) [application/x-bzip2]
Saving to: ‘httpd-2.4.62.tar.bz2’

httpd-2.4.62.tar.bz2       100%[=======================================>]   7.17M  2.13MB/s    in 3.4s

2026-04-26 20:35:55 (2.13 MB/s) - ‘httpd-2.4.62.tar.bz2’ saved [7521661/7521661]
# 4. Сборка с помощью rpmbuild -tb
[root@192 SOURCES]# rpmbuild -tb httpd-2.4.62.tar.bz2
warning: line 19: It's not recommended to have unversioned Obsoletes: Obsoletes: httpd-suexec
warning: line 34: It's not recommended to have unversioned Obsoletes: Obsoletes: secureweb-devel, apache-devel
warning: line 51: It's not recommended to have unversioned Obsoletes: Obsoletes: secureweb-manual, apache-manual
error: Failed build dependencies:
        libselinux-devel is needed by httpd-2.4.62-1.x86_64
        [root@192 SOURCES]# sudo dnf install libuuid-devel
Last metadata expiration check: 0:16:25 ago on Sun 26 Apr 2026 08:25:03 PM MSK.
Dependencies resolved.
===========================================================================================================
 Package                    Architecture        Version                       Repository              Size
===========================================================================================================
Installing:
 libuuid-devel              x86_64              2.37.4-25.el9                 appstream               23 k

Transaction Summary
===========================================================================================================
Install  1 Package

Total download size: 23 k
Installed size: 14 k
Is this ok [y/N]: y
Downloading Packages:
libuuid-devel-2.37.4-25.el9.x86_64.rpm                                      69 kB/s |  23 kB     00:00
-----------------------------------------------------------------------------------------------------------
Total                                                                      3.6 kB/s |  23 kB     00:06
Running transaction check
Transaction check succeeded.
Running transaction test
Transaction test succeeded.
Running transaction
  Preparing        :                                                                                   1/1
  Installing       : libuuid-devel-2.37.4-25.el9.x86_64                                                1/1
  Running scriptlet: libuuid-devel-2.37.4-25.el9.x86_64                                                1/1
  Verifying        : libuuid-devel-2.37.4-25.el9.x86_64                                                1/1

Installed:
  libuuid-devel-2.37.4-25.el9.x86_64

Complete!
 is needed by httpd-2.4.62-1.x86_64
        perl is needed by httpd-2.4.62-1.x86_64
[root@192 SOURCES]# sudo dnf install libselinux-devel
Last metadata expiration check: 0:14:52 ago on Sun 26 Apr 2026 08:25:03 PM MSK.
Dependencies resolved.
===========================================================================================================
 Package                       Architecture        Version                    Repository              Size
===========================================================================================================
Installing:
 libselinux-devel              x86_64              3.6-3.el9                  appstream              159 k
Installing dependencies:
 libsepol-devel                x86_64              3.6-3.el9                  appstream               47 k
 pcre2-devel                   x86_64              10.40-6.el9                appstream              512 k
 pcre2-utf16                   x86_64              10.40-6.el9                appstream              214 k

Transaction Summary
===========================================================================================================
Install  4 Packages

Total download size: 932 k
Installed size: 2.7 M
Is this ok [y/N]: y
Downloading Packages:
(1/4): libsepol-devel-3.6-3.el9.x86_64.rpm                                  65 kB/s |  47 kB     00:00
(2/4): libselinux-devel-3.6-3.el9.x86_64.rpm                               118 kB/s | 159 kB     00:01
(3/4): pcre2-utf16-10.40-6.el9.x86_64.rpm                                  209 kB/s | 214 kB     00:01
(4/4): pcre2-devel-10.40-6.el9.x86_64.rpm                                  244 kB/s | 512 kB     00:02
-----------------------------------------------------------------------------------------------------------
Total                                                                      368 kB/s | 932 kB     00:02
Running transaction check
Transaction check succeeded.
Running transaction test
Transaction test succeeded.
Running transaction
  Preparing        :                                                                                   1/1
  Installing       : pcre2-utf16-10.40-6.el9.x86_64                                                    1/4
  Installing       : pcre2-devel-10.40-6.el9.x86_64                                                    2/4
  Installing       : libsepol-devel-3.6-3.el9.x86_64                                                   3/4
  Installing       : libselinux-devel-3.6-3.el9.x86_64                                                 4/4
  Running scriptlet: libselinux-devel-3.6-3.el9.x86_64                                                 4/4
  Verifying        : libselinux-devel-3.6-3.el9.x86_64                                                 1/4
  Verifying        : libsepol-devel-3.6-3.el9.x86_64                                                   2/4
  Verifying        : pcre2-devel-10.40-6.el9.x86_64                                                    3/4
  Verifying        : pcre2-utf16-10.40-6.el9.x86_64                                                    4/4

Installed:
  libselinux-devel-3.6-3.el9.x86_64    libsepol-devel-3.6-3.el9.x86_64    pcre2-devel-10.40-6.el9.x86_64
  pcre2-utf16-10.40-6.el9.x86_64

Complete!
[root@192 SOURCES]# sudo dnf install perl
Last metadata expiration check: 0:17:13 ago on Sun 26 Apr 2026 08:25:03 PM MSK.
Dependencies resolved.
===========================================================================================================
 Package                              Architecture   Version                       Repository         Size
===========================================================================================================
Installing:
 perl                                 x86_64         4:5.32.1-483.el9              appstream         8.2 k
Installing dependencies:
 perl-Algorithm-Diff                  noarch         1.2010-4.el9                  appstream          48 k
 perl-Archive-Tar                     noarch         2.38-6.el9                    appstream          72 k
 perl-Archive-Zip                     noarch         1.68-6.el9                    appstream         112 k
 perl-Attribute-Handlers              noarch         1.01-483.el9                  appstream          27 k
 perl-AutoSplit                       noarch         5.74-483.el9                  appstream          21 k
 perl-Benchmark                       noarch         1.23-483.el9                  appstream          26 k
 perl-CPAN                            noarch         2.29-5.el9                    appstream         571 k
 perl-CPAN-Meta                       noarch         2.150010-460.el9              appstream         202 k
 perl-CPAN-Meta-Requirements          noarch         2.140-461.el9                 appstream          32 k
 perl-CPAN-Meta-YAML                  noarch         0.018-461.el9                 appstream          27 k
 perl-Compress-Bzip2                  x86_64         2.28-5.el9                    appstream          70 k
 perl-Compress-Raw-Bzip2              x86_64         2.101-5.el9                   appstream          35 k
 perl-Compress-Raw-Lzma               x86_64         2.101-3.el9                   appstream          51 k
 perl-Compress-Raw-Zlib               x86_64         2.101-5.el9                   appstream          61 k
 perl-Config-Extensions               noarch         0.03-483.el9                  appstream          12 k
 perl-Config-Perl-V                   noarch         0.33-4.el9                    appstream          22 k
 perl-DBM_Filter                      noarch         0.06-483.el9                  appstream          31 k
 perl-DB_File                         x86_64         1.855-4.el9                   appstream          82 k
 perl-Data-OptList                    noarch         0.110-17.el9                  appstream          27 k
 perl-Data-Section                    noarch         0.200007-14.el9               appstream          26 k
 perl-Devel-PPPort                    x86_64         3.62-4.el9                    appstream         212 k
 perl-Devel-Peek                      x86_64         1.28-483.el9                  appstream          32 k
 perl-Devel-SelfStubber               noarch         1.06-483.el9                  appstream          14 k
 perl-Devel-Size                      x86_64         0.83-10.el9                   appstream          32 k
 perl-Digest-SHA                      x86_64         1:6.02-461.el9                appstream          62 k
 perl-Digest-SHA1                     x86_64         2.13-34.el9                   appstream          53 k
 perl-DirHandle                       noarch         1.05-483.el9                  appstream          12 k
 perl-Dumpvalue                       noarch         2.27-483.el9                  appstream          18 k
 perl-Encode-devel                    x86_64         4:3.08-462.el9                appstream          42 k
 perl-English                         noarch         1.11-483.el9                  appstream          13 k
 perl-Env                             noarch         1.04-460.el9                  appstream          20 k
 perl-ExtUtils-CBuilder               noarch         1:0.280236-5.el9              appstream          48 k
 perl-ExtUtils-Command                noarch         2:7.60-3.el9                  appstream          15 k
 perl-ExtUtils-Constant               noarch         0.25-483.el9                  appstream          46 k
 perl-ExtUtils-Embed                  noarch         1.35-483.el9                  appstream          17 k
 perl-ExtUtils-Install                noarch         2.20-4.el9                    appstream          45 k
 perl-ExtUtils-MM-Utils               noarch         2:7.60-3.el9                  appstream          13 k
 perl-ExtUtils-MakeMaker              noarch         2:7.60-3.el9                  appstream         300 k
 perl-ExtUtils-Manifest               noarch         1:1.73-4.el9                  appstream          35 k
 perl-ExtUtils-Miniperl               noarch         1.09-483.el9                  appstream          15 k
 perl-ExtUtils-ParseXS                noarch         1:3.40-460.el9                appstream         186 k
 perl-File-DosGlob                    x86_64         1.12-483.el9                  appstream          19 k
 perl-File-Fetch                      noarch         1.00-4.el9                    appstream          31 k
 perl-File-HomeDir                    noarch         1.006-4.el9                   appstream          60 k
 perl-File-Which                      noarch         1.23-10.el9                   appstream          22 k
 perl-FileCache                       noarch         1.10-483.el9                  appstream          14 k
 perl-Filter                          x86_64         2:1.60-4.el9                  appstream          91 k
 perl-Filter-Simple                   noarch         0.96-460.el9                  appstream          28 k
 perl-FindBin                         noarch         1.51-483.el9                  appstream          14 k
 perl-GDBM_File                       x86_64         1.18-483.el9                  appstream          22 k
 perl-Hash-Util                       x86_64         0.23-483.el9                  appstream          34 k
 perl-Hash-Util-FieldHash             x86_64         1.20-483.el9                  appstream          37 k
 perl-I18N-Collate                    noarch         1.02-483.el9                  appstream          14 k
 perl-I18N-LangTags                   noarch         0.44-483.el9                  appstream          54 k
 perl-I18N-Langinfo                   x86_64         0.19-483.el9                  appstream          22 k
 perl-IO-Compress                     noarch         2.102-4.el9                   appstream         270 k
 perl-IO-Compress-Lzma                noarch         2.101-4.el9                   appstream          78 k
 perl-IO-Zlib                         noarch         1:1.11-4.el9                  appstream          20 k
 perl-IPC-Cmd                         noarch         2:1.04-461.el9                appstream          40 k
 perl-IPC-SysV                        x86_64         2.09-4.el9                    appstream          43 k
 perl-IPC-System-Simple               noarch         1.30-6.el9                    appstream          41 k
 perl-Importer                        noarch         0.026-4.el9                   appstream          40 k
 perl-JSON-PP                         noarch         1:4.06-4.el9                  appstream          67 k
 perl-Locale-Maketext                 noarch         1.29-461.el9                  appstream          95 k
 perl-Locale-Maketext-Simple          noarch         1:0.21-483.el9                appstream          17 k
 perl-MIME-Charset                    noarch         1.012.2-15.el9                appstream          49 k
 perl-MRO-Compat                      noarch         0.13-15.el9                   appstream          20 k
 perl-Math-BigInt-FastCalc            x86_64         0.500.900-460.el9             appstream          28 k
 perl-Math-BigRat                     noarch         0.2614-460.el9                appstream          39 k
 perl-Memoize                         noarch         1.03-483.el9                  appstream          56 k
 perl-Module-Build                    noarch         2:0.42.31-9.el9               appstream         263 k
 perl-Module-CoreList                 noarch         1:5.20240609-1.el9            appstream          88 k
 perl-Module-CoreList-tools           noarch         1:5.20240609-1.el9            appstream          17 k
 perl-Module-Load                     noarch         1:0.36-4.el9                  appstream          18 k
 perl-Module-Load-Conditional         noarch         0.74-4.el9                    appstream          23 k
 perl-Module-Loaded                   noarch         1:0.08-483.el9                appstream          13 k
 perl-Module-Metadata                 noarch         1.000037-460.el9              appstream          36 k
 perl-Module-Signature                noarch         0.88-1.el9                    appstream          84 k
 perl-NEXT                            noarch         0.67-483.el9                  appstream          21 k
 perl-Net                             noarch         1.02-483.el9                  appstream          25 k
 perl-Net-Ping                        noarch         2.74-5.el9                    appstream          50 k
 perl-ODBM_File                       x86_64         1.16-483.el9                  appstream          22 k
 perl-Object-HashBase                 noarch         0.009-7.el9                   appstream          26 k
 perl-Opcode                          x86_64         1.48-483.el9                  appstream          36 k
 perl-Package-Generator               noarch         1.106-23.el9                  appstream          24 k
 perl-Params-Check                    noarch         1:0.38-461.el9                appstream          23 k
 perl-Params-Util                     x86_64         1.102-5.el9                   appstream          34 k
 perl-Perl-OSType                     noarch         1.010-461.el9                 appstream          24 k
 perl-PerlIO-via-QuotedPrint          noarch         0.09-4.el9                    appstream          23 k
 perl-Pod-Checker                     noarch         4:1.74-4.el9                  appstream          33 k
 perl-Pod-Functions                   noarch         1.13-483.el9                  appstream          13 k
 perl-Pod-Html                        noarch         1.25-483.el9                  appstream          26 k
 perl-Safe                            noarch         2.41-483.el9                  appstream          25 k
 perl-Search-Dict                     noarch         1.07-483.el9                  appstream          13 k
 perl-SelfLoader                      noarch         1.26-483.el9                  appstream          21 k
 perl-Software-License                noarch         0.103014-12.el9               appstream         140 k
 perl-Sub-Exporter                    noarch         0.987-27.el9                  appstream          73 k
 perl-Sub-Install                     noarch         0.928-28.el9                  appstream          23 k
 perl-Sys-Hostname                    x86_64         1.23-483.el9                  appstream          17 k
 perl-Sys-Syslog                      x86_64         0.36-461.el9                  appstream          48 k
 perl-Term-Complete                   noarch         1.403-483.el9                 appstream          13 k
 perl-Term-ReadLine                   noarch         1.17-483.el9                  appstream          19 k
 perl-Term-Size-Perl                  x86_64         0.031-12.el9                  appstream          22 k
 perl-Term-Table                      noarch         0.015-8.el9                   appstream          36 k
 perl-Test                            noarch         1.31-483.el9                  appstream          28 k
 perl-Test-Harness                    noarch         1:3.42-461.el9                appstream         295 k
 perl-Test-Simple                     noarch         3:1.302183-4.el9              appstream         626 k
 perl-Text-Abbrev                     noarch         1.02-483.el9                  appstream          12 k
 perl-Text-Balanced                   noarch         2.04-4.el9                    appstream          48 k
 perl-Text-Diff                       noarch         1.45-13.el9                   appstream          42 k
 perl-Text-Glob                       noarch         0.11-15.el9                   appstream          14 k
 perl-Text-Template                   noarch         1.59-5.el9                    appstream          61 k
 perl-Thread                          noarch         3.05-483.el9                  appstream          18 k
 perl-Thread-Semaphore                noarch         2.13-483.el9                  appstream          15 k
 perl-Tie                             noarch         4.6-483.el9                   appstream          31 k
 perl-Tie-File                        noarch         1.06-483.el9                  appstream          43 k
 perl-Tie-Memoize                     noarch         1.1-483.el9                   appstream          14 k
 perl-Tie-RefHash                     noarch         1.40-4.el9                    appstream          24 k
 perl-Time                            noarch         1.03-483.el9                  appstream          18 k
 perl-Time-HiRes                      x86_64         4:1.9764-462.el9              appstream          58 k
 perl-Time-Piece                      x86_64         1.3401-483.el9                appstream          40 k
 perl-Unicode-Collate                 x86_64         1.29-4.el9                    appstream         760 k
 perl-Unicode-Normalize               x86_64         1.27-461.el9                  appstream          91 k
 perl-Unicode-UCD                     noarch         0.75-483.el9                  appstream          78 k
 perl-User-pwent                      noarch         1.03-483.el9                  appstream          20 k
 perl-autodie                         noarch         2.34-4.el9                    appstream          97 k
 perl-autouse                         noarch         1.11-483.el9                  appstream          13 k
 perl-bignum                          noarch         0.51-460.el9                  appstream          43 k
 perl-blib                            noarch         1.07-483.el9                  appstream          12 k
 perl-debugger                        noarch         1.56-483.el9                  appstream         133 k
 perl-deprecate                       noarch         0.04-483.el9                  appstream          14 k
 perl-devel                           x86_64         4:5.32.1-483.el9              appstream         676 k
 perl-diagnostics                     noarch         1.37-483.el9                  appstream         210 k
 perl-doc                             noarch         5.32.1-483.el9                appstream         4.6 M
 perl-encoding                        x86_64         4:3.00-462.el9                appstream          63 k
 perl-encoding-warnings               noarch         0.13-483.el9                  appstream          16 k
 perl-experimental                    noarch         0.022-6.el9                   appstream          22 k
 perl-fields                          noarch         2.27-483.el9                  appstream          16 k
 perl-filetest                        noarch         1.03-483.el9                  appstream          14 k
 perl-inc-latest                      noarch         2:0.500-20.el9                appstream          25 k
 perl-less                            noarch         0.03-483.el9                  appstream          13 k
 perl-libnetcfg                       noarch         4:5.32.1-483.el9              appstream          16 k
 perl-local-lib                       noarch         2.000024-13.el9               appstream          68 k
 perl-meta-notation                   noarch         5.32.1-483.el9                appstream         9.3 k
 perl-open                            noarch         1.12-483.el9                  appstream          16 k
 perl-perlfaq                         noarch         5.20210520-1.el9              appstream         376 k
 perl-ph                              x86_64         5.32.1-483.el9                appstream          45 k
 perl-sigtrap                         noarch         1.09-483.el9                  appstream          15 k
 perl-sort                            noarch         2.04-483.el9                  appstream          13 k
 perl-utils                           noarch         5.32.1-483.el9                appstream          55 k
 perl-vmsish                          noarch         1.04-483.el9                  appstream          14 k
 python3-pyparsing                    noarch         2.4.7-9.el9                   baseos            150 k
 sombok                               x86_64         2.4.0-16.el9                  appstream          48 k
 systemtap-sdt-devel                  x86_64         5.4-4.el9                     appstream          68 k
 systemtap-sdt-dtrace                 x86_64         5.4-4.el9                     appstream          69 k
Installing weak dependencies:
 perl-CPAN-DistnameInfo               noarch         0.12-23.el9                   appstream          15 k
 perl-Encode-Locale                   noarch         1.05-21.el9                   appstream          20 k
 perl-Term-Size-Any                   noarch         0.002-35.el9                  appstream          14 k
 perl-Unicode-LineBreak               x86_64         2019.001-11.el9               appstream         125 k

Transaction Summary
===========================================================================================================
Install  160 Packages

Total download size: 15 M
Installed size: 43 M
Is this ok [y/N]: y
Downloading Packages:
(1/160): perl-5.32.1-483.el9.x86_64.rpm                                     38 kB/s | 8.2 kB     00:00
(2/160): perl-Algorithm-Diff-1.2010-4.el9.noarch.rpm                       106 kB/s |  48 kB     00:00
(3/160): python3-pyparsing-2.4.7-9.el9.noarch.rpm                          170 kB/s | 150 kB     00:00
(4/160): perl-Archive-Tar-2.38-6.el9.noarch.rpm                            107 kB/s |  72 kB     00:00
(5/160): perl-Attribute-Handlers-1.01-483.el9.noarch.rpm                   211 kB/s |  27 kB     00:00
(6/160): perl-Archive-Zip-1.68-6.el9.noarch.rpm                            193 kB/s | 112 kB     00:00
(7/160): perl-AutoSplit-5.74-483.el9.noarch.rpm                            109 kB/s |  21 kB     00:00
(8/160): perl-Benchmark-1.23-483.el9.noarch.rpm                            118 kB/s |  26 kB     00:00
(9/160): perl-CPAN-DistnameInfo-0.12-23.el9.noarch.rpm                      26 kB/s |  15 kB     00:00
(10/160): perl-CPAN-Meta-Requirements-2.140-461.el9.noarch.rpm             172 kB/s |  32 kB     00:00
(11/160): perl-CPAN-Meta-YAML-0.018-461.el9.noarch.rpm                     169 kB/s |  27 kB     00:00
(12/160): perl-Compress-Bzip2-2.28-5.el9.x86_64.rpm                        333 kB/s |  70 kB     00:00
(13/160): perl-CPAN-Meta-2.150010-460.el9.noarch.rpm                       179 kB/s | 202 kB     00:01
(14/160): perl-Compress-Raw-Bzip2-2.101-5.el9.x86_64.rpm                   254 kB/s |  35 kB     00:00
(15/160): perl-Compress-Raw-Lzma-2.101-3.el9.x86_64.rpm                    317 kB/s |  51 kB     00:00
(16/160): perl-Compress-Raw-Zlib-2.101-5.el9.x86_64.rpm                    168 kB/s |  61 kB     00:00
(17/160): perl-Config-Extensions-0.03-483.el9.noarch.rpm                    52 kB/s |  12 kB     00:00
(18/160): perl-Config-Perl-V-0.33-4.el9.noarch.rpm                         176 kB/s |  22 kB     00:00
(19/160): perl-CPAN-2.29-5.el9.noarch.rpm                                  290 kB/s | 571 kB     00:01
(20/160): perl-DBM_Filter-0.06-483.el9.noarch.rpm                           64 kB/s |  31 kB     00:00
(21/160): perl-Data-OptList-0.110-17.el9.noarch.rpm                         89 kB/s |  27 kB     00:00
(22/160): perl-Data-Section-0.200007-14.el9.noarch.rpm                      93 kB/s |  26 kB     00:00
(23/160): perl-DB_File-1.855-4.el9.x86_64.rpm                              120 kB/s |  82 kB     00:00
(24/160): perl-Devel-Peek-1.28-483.el9.x86_64.rpm                          116 kB/s |  32 kB     00:00
(25/160): perl-Devel-PPPort-3.62-4.el9.x86_64.rpm                          391 kB/s | 212 kB     00:00
(26/160): perl-Devel-SelfStubber-1.06-483.el9.noarch.rpm                    32 kB/s |  14 kB     00:00
(27/160): perl-Devel-Size-0.83-10.el9.x86_64.rpm                           111 kB/s |  32 kB     00:00
(28/160): perl-Digest-SHA-6.02-461.el9.x86_64.rpm                          110 kB/s |  62 kB     00:00
(29/160): perl-Dumpvalue-2.27-483.el9.noarch.rpm                           101 kB/s |  18 kB     00:00
(30/160): perl-DirHandle-1.05-483.el9.noarch.rpm                            23 kB/s |  12 kB     00:00
(31/160): perl-Digest-SHA1-2.13-34.el9.x86_64.rpm                           81 kB/s |  53 kB     00:00
(32/160): perl-Encode-Locale-1.05-21.el9.noarch.rpm                         94 kB/s |  20 kB     00:00
(33/160): perl-English-1.11-483.el9.noarch.rpm                              26 kB/s |  13 kB     00:00
(34/160): perl-Encode-devel-3.08-462.el9.x86_64.rpm                         75 kB/s |  42 kB     00:00
(35/160): perl-Env-1.04-460.el9.noarch.rpm                                  42 kB/s |  20 kB     00:00
(36/160): perl-ExtUtils-Command-7.60-3.el9.noarch.rpm                       55 kB/s |  15 kB     00:00
(37/160): perl-ExtUtils-CBuilder-0.280236-5.el9.noarch.rpm                 134 kB/s |  48 kB     00:00
(38/160): perl-ExtUtils-Constant-0.25-483.el9.noarch.rpm                   110 kB/s |  46 kB     00:00
(39/160): perl-ExtUtils-Embed-1.35-483.el9.noarch.rpm                       61 kB/s |  17 kB     00:00
(40/160): perl-ExtUtils-MM-Utils-7.60-3.el9.noarch.rpm                      70 kB/s |  13 kB     00:00
(41/160): perl-ExtUtils-Install-2.20-4.el9.noarch.rpm                       51 kB/s |  45 kB     00:00
(42/160): perl-ExtUtils-MakeMaker-7.60-3.el9.noarch.rpm                    419 kB/s | 300 kB     00:00
(43/160): perl-ExtUtils-Miniperl-1.09-483.el9.noarch.rpm                   179 kB/s |  15 kB     00:00
(44/160): perl-File-DosGlob-1.12-483.el9.x86_64.rpm                         68 kB/s |  19 kB     00:00
(45/160): perl-ExtUtils-Manifest-1.73-4.el9.noarch.rpm                      37 kB/s |  35 kB     00:00
(46/160): perl-File-Fetch-1.00-4.el9.noarch.rpm                            220 kB/s |  31 kB     00:00
(47/160): perl-File-Which-1.23-10.el9.noarch.rpm                            76 kB/s |  22 kB     00:00
(48/160): perl-File-HomeDir-1.006-4.el9.noarch.rpm                         172 kB/s |  60 kB     00:00
(49/160): perl-FileCache-1.10-483.el9.noarch.rpm                           102 kB/s |  14 kB     00:00
(50/160): perl-Filter-Simple-0.96-460.el9.noarch.rpm                       104 kB/s |  28 kB     00:00
(51/160): perl-Filter-1.60-4.el9.x86_64.rpm                                213 kB/s |  91 kB     00:00
(52/160): perl-FindBin-1.51-483.el9.noarch.rpm                              93 kB/s |  14 kB     00:00
(53/160): perl-GDBM_File-1.18-483.el9.x86_64.rpm                            89 kB/s |  22 kB     00:00
(54/160): perl-ExtUtils-ParseXS-3.40-460.el9.noarch.rpm                    124 kB/s | 186 kB     00:01
(55/160): perl-Hash-Util-FieldHash-1.20-483.el9.x86_64.rpm                 109 kB/s |  37 kB     00:00
(56/160): perl-Hash-Util-0.23-483.el9.x86_64.rpm                            68 kB/s |  34 kB     00:00
(57/160): perl-I18N-LangTags-0.44-483.el9.noarch.rpm                       186 kB/s |  54 kB     00:00
(58/160): perl-I18N-Collate-1.02-483.el9.noarch.rpm                         18 kB/s |  14 kB     00:00
(59/160): perl-I18N-Langinfo-0.19-483.el9.x86_64.rpm                        41 kB/s |  22 kB     00:00
(60/160): perl-IO-Zlib-1.11-4.el9.noarch.rpm                                62 kB/s |  20 kB     00:00
(61/160): perl-IO-Compress-Lzma-2.101-4.el9.noarch.rpm                     196 kB/s |  78 kB     00:00
(62/160): perl-IO-Compress-2.102-4.el9.noarch.rpm                          409 kB/s | 270 kB     00:00
(63/160): perl-IPC-Cmd-1.04-461.el9.noarch.rpm                             292 kB/s |  40 kB     00:00
(64/160): perl-IPC-SysV-2.09-4.el9.x86_64.rpm                              173 kB/s |  43 kB     00:00
(65/160): perl-IPC-System-Simple-1.30-6.el9.noarch.rpm                     129 kB/s |  41 kB     00:00
(66/160): perl-Importer-0.026-4.el9.noarch.rpm                              66 kB/s |  40 kB     00:00
(67/160): perl-Locale-Maketext-Simple-0.21-483.el9.noarch.rpm               94 kB/s |  17 kB     00:00
(68/160): perl-JSON-PP-4.06-4.el9.noarch.rpm                                97 kB/s |  67 kB     00:00
(69/160): perl-MIME-Charset-1.012.2-15.el9.noarch.rpm                      196 kB/s |  49 kB     00:00
(70/160): perl-MRO-Compat-0.13-15.el9.noarch.rpm                            85 kB/s |  20 kB     00:00
(71/160): perl-Locale-Maketext-1.29-461.el9.noarch.rpm                     113 kB/s |  95 kB     00:00
(72/160): perl-Math-BigInt-FastCalc-0.500.900-460.el9.x86_64.rpm           169 kB/s |  28 kB     00:00
(73/160): perl-Math-BigRat-0.2614-460.el9.noarch.rpm                        74 kB/s |  39 kB     00:00
(74/160): perl-Memoize-1.03-483.el9.noarch.rpm                              84 kB/s |  56 kB     00:00
(75/160): perl-Module-CoreList-tools-5.20240609-1.el9.noarch.rpm           106 kB/s |  17 kB     00:00
(76/160): perl-Module-CoreList-5.20240609-1.el9.noarch.rpm                 249 kB/s |  88 kB     00:00
(77/160): perl-Module-Load-0.36-4.el9.noarch.rpm                           112 kB/s |  18 kB     00:00
(78/160): perl-Module-Load-Conditional-0.74-4.el9.noarch.rpm                94 kB/s |  23 kB     00:00
(79/160): perl-Module-Loaded-0.08-483.el9.noarch.rpm                        48 kB/s |  13 kB     00:00
(80/160): perl-Module-Build-0.42.31-9.el9.noarch.rpm                       218 kB/s | 263 kB     00:01
(81/160): perl-Module-Metadata-1.000037-460.el9.noarch.rpm                  99 kB/s |  36 kB     00:00
(82/160): perl-Module-Signature-0.88-1.el9.noarch.rpm                      200 kB/s |  84 kB     00:00
(83/160): perl-NEXT-0.67-483.el9.noarch.rpm                                 41 kB/s |  21 kB     00:00
(84/160): perl-Net-1.02-483.el9.noarch.rpm                                  44 kB/s |  25 kB     00:00
(85/160): perl-Net-Ping-2.74-5.el9.noarch.rpm                              134 kB/s |  50 kB     00:00
(86/160): perl-ODBM_File-1.16-483.el9.x86_64.rpm                            48 kB/s |  22 kB     00:00
(87/160): perl-Object-HashBase-0.009-7.el9.noarch.rpm                      103 kB/s |  26 kB     00:00
(88/160): perl-Package-Generator-1.106-23.el9.noarch.rpm                    79 kB/s |  24 kB     00:00
(89/160): perl-Opcode-1.48-483.el9.x86_64.rpm                               60 kB/s |  36 kB     00:00
(90/160): perl-Params-Util-1.102-5.el9.x86_64.rpm                          119 kB/s |  34 kB     00:00
(91/160): perl-PerlIO-via-QuotedPrint-0.09-4.el9.noarch.rpm                106 kB/s |  23 kB     00:00
(92/160): perl-Perl-OSType-1.010-461.el9.noarch.rpm                         46 kB/s |  24 kB     00:00
(93/160): perl-Params-Check-0.38-461.el9.noarch.rpm                         26 kB/s |  23 kB     00:00
(94/160): perl-Pod-Checker-1.74-4.el9.noarch.rpm                           158 kB/s |  33 kB     00:00
(95/160): perl-Pod-Functions-1.13-483.el9.noarch.rpm                        59 kB/s |  13 kB     00:00
(96/160): perl-Pod-Html-1.25-483.el9.noarch.rpm                             64 kB/s |  26 kB     00:00
(97/160): perl-Safe-2.41-483.el9.noarch.rpm                                 45 kB/s |  25 kB     00:00
(98/160): perl-SelfLoader-1.26-483.el9.noarch.rpm                           59 kB/s |  21 kB     00:00
(99/160): perl-Search-Dict-1.07-483.el9.noarch.rpm                          21 kB/s |  13 kB     00:00
(100/160): perl-Software-License-0.103014-12.el9.noarch.rpm                242 kB/s | 140 kB     00:00
(101/160): perl-Sys-Hostname-1.23-483.el9.x86_64.rpm                       190 kB/s |  17 kB     00:00
(102/160): perl-Sub-Install-0.928-28.el9.noarch.rpm                         36 kB/s |  23 kB     00:00
(103/160): perl-Sub-Exporter-0.987-27.el9.noarch.rpm                       106 kB/s |  73 kB     00:00
(104/160): perl-Sys-Syslog-0.36-461.el9.x86_64.rpm                         237 kB/s |  48 kB     00:00
(105/160): perl-Term-Complete-1.403-483.el9.noarch.rpm                      58 kB/s |  13 kB     00:00
(106/160): perl-Term-ReadLine-1.17-483.el9.noarch.rpm                       43 kB/s |  19 kB     00:00
(107/160): perl-Term-Size-Any-0.002-35.el9.noarch.rpm                       29 kB/s |  14 kB     00:00
(108/160): perl-Term-Size-Perl-0.031-12.el9.x86_64.rpm                      36 kB/s |  22 kB     00:00
(109/160): perl-Term-Table-0.015-8.el9.noarch.rpm                           62 kB/s |  36 kB     00:00
(110/160): perl-Test-1.31-483.el9.noarch.rpm                                54 kB/s |  28 kB     00:00
(111/160): perl-Text-Abbrev-1.02-483.el9.noarch.rpm                         65 kB/s |  12 kB     00:00
(112/160): perl-Text-Balanced-2.04-4.el9.noarch.rpm                        172 kB/s |  48 kB     00:00
(113/160): perl-Test-Harness-3.42-461.el9.noarch.rpm                       317 kB/s | 295 kB     00:00
(114/160): perl-Text-Diff-1.45-13.el9.noarch.rpm                           195 kB/s |  42 kB     00:00
(115/160): perl-Text-Glob-0.11-15.el9.noarch.rpm                           114 kB/s |  14 kB     00:00
(116/160): perl-Text-Template-1.59-5.el9.noarch.rpm                        187 kB/s |  61 kB     00:00
(117/160): perl-Thread-3.05-483.el9.noarch.rpm                              62 kB/s |  18 kB     00:00
(118/160): perl-Thread-Semaphore-2.13-483.el9.noarch.rpm                    92 kB/s |  15 kB     00:00
(119/160): perl-Tie-4.6-483.el9.noarch.rpm                                  67 kB/s |  31 kB     00:00
(120/160): perl-Tie-File-1.06-483.el9.noarch.rpm                           129 kB/s |  43 kB     00:00
(121/160): perl-Tie-Memoize-1.1-483.el9.noarch.rpm                         128 kB/s |  14 kB     00:00
(122/160): perl-Tie-RefHash-1.40-4.el9.noarch.rpm                          104 kB/s |  24 kB     00:00
(123/160): perl-Time-1.03-483.el9.noarch.rpm                                44 kB/s |  18 kB     00:00
(124/160): perl-Test-Simple-1.302183-4.el9.noarch.rpm                      293 kB/s | 626 kB     00:02
(125/160): perl-Time-Piece-1.3401-483.el9.x86_64.rpm                       147 kB/s |  40 kB     00:00
(126/160): perl-Time-HiRes-1.9764-462.el9.x86_64.rpm                        97 kB/s |  58 kB     00:00
(127/160): perl-Unicode-LineBreak-2019.001-11.el9.x86_64.rpm               310 kB/s | 125 kB     00:00
(128/160): perl-Unicode-UCD-0.75-483.el9.noarch.rpm                        236 kB/s |  78 kB     00:00
(129/160): perl-Unicode-Collate-1.29-4.el9.x86_64.rpm                      710 kB/s | 760 kB     00:01
(130/160): perl-User-pwent-1.03-483.el9.noarch.rpm                         245 kB/s |  20 kB     00:00
(131/160): perl-Unicode-Normalize-1.27-461.el9.x86_64.rpm                  109 kB/s |  91 kB     00:00
(132/160): perl-autodie-2.34-4.el9.noarch.rpm                              424 kB/s |  97 kB     00:00
(133/160): perl-autouse-1.11-483.el9.noarch.rpm                             49 kB/s |  13 kB     00:00
(134/160): perl-bignum-0.51-460.el9.noarch.rpm                              77 kB/s |  43 kB     00:00
(135/160): perl-blib-1.07-483.el9.noarch.rpm                                24 kB/s |  12 kB     00:00
(136/160): perl-deprecate-0.04-483.el9.noarch.rpm                           65 kB/s |  14 kB     00:00
(137/160): perl-debugger-1.56-483.el9.noarch.rpm                           133 kB/s | 133 kB     00:01
(138/160): perl-diagnostics-1.37-483.el9.noarch.rpm                        219 kB/s | 210 kB     00:00
(139/160): perl-encoding-3.00-462.el9.x86_64.rpm                           393 kB/s |  63 kB     00:00
(140/160): perl-devel-5.32.1-483.el9.x86_64.rpm                            502 kB/s | 676 kB     00:01
(141/160): perl-encoding-warnings-0.13-483.el9.noarch.rpm                  174 kB/s |  16 kB     00:00
(142/160): perl-experimental-0.022-6.el9.noarch.rpm                        164 kB/s |  22 kB     00:00
(143/160): perl-fields-2.27-483.el9.noarch.rpm                              38 kB/s |  16 kB     00:00
(144/160): perl-filetest-1.03-483.el9.noarch.rpm                            47 kB/s |  14 kB     00:00
(145/160): perl-inc-latest-0.500-20.el9.noarch.rpm                         203 kB/s |  25 kB     00:00
(146/160): perl-less-0.03-483.el9.noarch.rpm                                38 kB/s |  13 kB     00:00
(147/160): perl-libnetcfg-5.32.1-483.el9.noarch.rpm                         29 kB/s |  16 kB     00:00
(148/160): perl-local-lib-2.000024-13.el9.noarch.rpm                       159 kB/s |  68 kB     00:00
(149/160): perl-meta-notation-5.32.1-483.el9.noarch.rpm                     92 kB/s | 9.3 kB     00:00
(150/160): perl-open-1.12-483.el9.noarch.rpm                                49 kB/s |  16 kB     00:00
(151/160): perl-ph-5.32.1-483.el9.x86_64.rpm                               188 kB/s |  45 kB     00:00
(152/160): perl-sigtrap-1.09-483.el9.noarch.rpm                            179 kB/s |  15 kB     00:00
(153/160): perl-perlfaq-5.20210520-1.el9.noarch.rpm                        555 kB/s | 376 kB     00:00
(154/160): perl-sort-2.04-483.el9.noarch.rpm                                98 kB/s |  13 kB     00:00
(155/160): perl-utils-5.32.1-483.el9.noarch.rpm                            204 kB/s |  55 kB     00:00
(156/160): perl-vmsish-1.04-483.el9.noarch.rpm                              47 kB/s |  14 kB     00:00
(157/160): sombok-2.4.0-16.el9.x86_64.rpm                                  171 kB/s |  48 kB     00:00
(158/160): systemtap-sdt-devel-5.4-4.el9.x86_64.rpm                        159 kB/s |  68 kB     00:00
(159/160): systemtap-sdt-dtrace-5.4-4.el9.x86_64.rpm                       198 kB/s |  69 kB     00:00
(160/160): perl-doc-5.32.1-483.el9.noarch.rpm                              1.1 MB/s | 4.6 MB     00:04
-----------------------------------------------------------------------------------------------------------
Total                                                                       96 kB/s |  15 MB     02:36
Running transaction check
Transaction check succeeded.
Running transaction test
Transaction test succeeded.
Running transaction
  Preparing        :                                                                                   1/1
  Installing       : perl-Time-HiRes-4:1.9764-462.el9.x86_64                                         1/160
  Installing       : perl-ExtUtils-Manifest-1:1.73-4.el9.noarch                                      2/160
  Installing       : perl-JSON-PP-1:4.06-4.el9.noarch                                                3/160
  Installing       : perl-ExtUtils-ParseXS-1:3.40-460.el9.noarch                                     4/160
  Installing       : perl-Compress-Raw-Zlib-2.101-5.el9.x86_64                                       5/160
  Installing       : perl-CPAN-Meta-Requirements-2.140-461.el9.noarch                                6/160
  Installing       : perl-meta-notation-5.32.1-483.el9.noarch                                        7/160
  Installing       : perl-Unicode-Normalize-1.27-461.el9.x86_64                                      8/160
  Installing       : perl-Tie-4.6-483.el9.noarch                                                     9/160
  Installing       : perl-Term-ReadLine-1.17-483.el9.noarch                                         10/160
  Installing       : perl-Perl-OSType-1.010-461.el9.noarch                                          11/160
  Installing       : perl-Module-Metadata-1.000037-460.el9.noarch                                   12/160
  Installing       : perl-Module-Load-1:0.36-4.el9.noarch                                           13/160
  Installing       : perl-Module-CoreList-1:5.20240609-1.el9.noarch                                 14/160
  Installing       : perl-Filter-2:1.60-4.el9.x86_64                                                15/160
  Installing       : perl-Digest-SHA-1:6.02-461.el9.x86_64                                          16/160
  Installing       : perl-Devel-Peek-1.28-483.el9.x86_64                                            17/160
  Installing       : perl-Dumpvalue-2.27-483.el9.noarch                                             18/160
  Installing       : perl-encoding-4:3.00-462.el9.x86_64                                            19/160
  Installing       : perl-Net-Ping-2.74-5.el9.noarch                                                20/160
  Installing       : perl-doc-5.32.1-483.el9.noarch                                                 21/160
  Installing       : perl-autouse-1.11-483.el9.noarch                                               22/160
  Installing       : perl-User-pwent-1.03-483.el9.noarch                                            23/160
  Installing       : perl-Tie-RefHash-1.40-4.el9.noarch                                             24/160
  Installing       : perl-Text-Balanced-2.04-4.el9.noarch                                           25/160
  Installing       : perl-Sys-Hostname-1.23-483.el9.x86_64                                          26/160
  Installing       : perl-Sub-Install-0.928-28.el9.noarch                                           27/160
  Installing       : perl-SelfLoader-1.26-483.el9.noarch                                            28/160
  Installing       : perl-Pod-Html-1.25-483.el9.noarch                                              29/160
  Installing       : perl-Params-Util-1.102-5.el9.x86_64                                            30/160
  Installing       : perl-Opcode-1.48-483.el9.x86_64                                                31/160
  Installing       : perl-Safe-2.41-483.el9.noarch                                                  32/160
  Installing       : perl-Math-BigRat-0.2614-460.el9.noarch                                         33/160
  Installing       : perl-I18N-Langinfo-0.19-483.el9.x86_64                                         34/160
  Installing       : perl-I18N-LangTags-0.44-483.el9.noarch                                         35/160
  Installing       : perl-Locale-Maketext-1.29-461.el9.noarch                                       36/160
  Installing       : perl-Locale-Maketext-Simple-1:0.21-483.el9.noarch                              37/160
  Installing       : perl-Params-Check-1:0.38-461.el9.noarch                                        38/160
  Installing       : perl-Module-Load-Conditional-0.74-4.el9.noarch                                 39/160
  Installing       : perl-Hash-Util-FieldHash-1.20-483.el9.x86_64                                   40/160
  Installing       : perl-Hash-Util-0.23-483.el9.x86_64                                             41/160
  Installing       : perl-ExtUtils-MM-Utils-2:7.60-3.el9.noarch                                     42/160
  Installing       : perl-IPC-Cmd-2:1.04-461.el9.noarch                                             43/160
  Installing       : perl-ExtUtils-Constant-0.25-483.el9.noarch                                     44/160
  Installing       : perl-ExtUtils-Command-2:7.60-3.el9.noarch                                      45/160
  Installing       : perl-DirHandle-1.05-483.el9.noarch                                             46/160
  Installing       : perl-Devel-PPPort-3.62-4.el9.x86_64                                            47/160
  Installing       : perl-Compress-Raw-Bzip2-2.101-5.el9.x86_64                                     48/160
  Installing       : perl-IO-Compress-2.102-4.el9.noarch                                            49/160
  Installing       : perl-IO-Zlib-1:1.11-4.el9.noarch                                               50/160
  Installing       : perl-CPAN-Meta-YAML-0.018-461.el9.noarch                                       51/160
  Installing       : perl-CPAN-Meta-2.150010-460.el9.noarch                                         52/160
  Installing       : perl-Benchmark-1.23-483.el9.noarch                                             53/160
  Installing       : perl-Test-Harness-1:3.42-461.el9.noarch                                        54/160
  Installing       : perl-AutoSplit-5.74-483.el9.noarch                                             55/160
  Installing       : perl-DBM_Filter-0.06-483.el9.noarch                                            56/160
  Installing       : perl-File-Fetch-1.00-4.el9.noarch                                              57/160
  Installing       : perl-fields-2.27-483.el9.noarch                                                58/160
  Installing       : perl-Encode-Locale-1.05-21.el9.noarch                                          59/160
  Installing       : perl-bignum-0.51-460.el9.noarch                                                60/160
  Installing       : perl-Data-OptList-0.110-17.el9.noarch                                          61/160
  Installing       : perl-Devel-SelfStubber-1.06-483.el9.noarch                                     62/160
  Installing       : perl-Filter-Simple-0.96-460.el9.noarch                                         63/160
  Installing       : perl-open-1.12-483.el9.noarch                                                  64/160
  Installing       : perl-debugger-1.56-483.el9.noarch                                              65/160
  Installing       : perl-Module-CoreList-tools-1:5.20240609-1.el9.noarch                           66/160
  Installing       : perl-Env-1.04-460.el9.noarch                                                   67/160
  Installing       : perl-Unicode-Collate-1.29-4.el9.x86_64                                         68/160
  Installing       : perl-Unicode-UCD-0.75-483.el9.noarch                                           69/160
  Installing       : perl-sigtrap-1.09-483.el9.noarch                                               70/160
  Installing       : perl-Archive-Zip-1.68-6.el9.noarch                                             71/160
  Installing       : sombok-2.4.0-16.el9.x86_64                                                     72/160
  Installing       : perl-vmsish-1.04-483.el9.noarch                                                73/160
  Installing       : perl-utils-5.32.1-483.el9.noarch                                               74/160
  Installing       : perl-sort-2.04-483.el9.noarch                                                  75/160
  Installing       : perl-ph-5.32.1-483.el9.x86_64                                                  76/160
  Installing       : perl-perlfaq-5.20210520-1.el9.noarch                                           77/160
  Installing       : perl-local-lib-2.000024-13.el9.noarch                                          78/160
  Installing       : perl-less-0.03-483.el9.noarch                                                  79/160
  Installing       : perl-filetest-1.03-483.el9.noarch                                              80/160
  Installing       : perl-experimental-0.022-6.el9.noarch                                           81/160
  Installing       : perl-encoding-warnings-0.13-483.el9.noarch                                     82/160
  Installing       : perl-diagnostics-1.37-483.el9.noarch                                           83/160
  Installing       : perl-deprecate-0.04-483.el9.noarch                                             84/160
  Installing       : perl-blib-1.07-483.el9.noarch                                                  85/160
  Installing       : perl-Time-Piece-1.3401-483.el9.x86_64                                          86/160
  Installing       : perl-Time-1.03-483.el9.noarch                                                  87/160
  Installing       : perl-Tie-Memoize-1.1-483.el9.noarch                                            88/160
  Installing       : perl-Tie-File-1.06-483.el9.noarch                                              89/160
  Installing       : perl-Thread-Semaphore-2.13-483.el9.noarch                                      90/160
  Installing       : perl-Thread-3.05-483.el9.noarch                                                91/160
  Installing       : perl-Text-Template-1.59-5.el9.noarch                                           92/160
  Installing       : perl-Text-Glob-0.11-15.el9.noarch                                              93/160
  Installing       : perl-Text-Abbrev-1.02-483.el9.noarch                                           94/160
  Installing       : perl-Test-1.31-483.el9.noarch                                                  95/160
  Installing       : perl-Term-Size-Perl-0.031-12.el9.x86_64                                        96/160
  Installing       : perl-Term-Size-Any-0.002-35.el9.noarch                                         97/160
  Installing       : perl-Term-Complete-1.403-483.el9.noarch                                        98/160
  Installing       : perl-Sys-Syslog-0.36-461.el9.x86_64                                            99/160
  Installing       : perl-Search-Dict-1.07-483.el9.noarch                                          100/160
  Installing       : perl-Pod-Functions-1.13-483.el9.noarch                                        101/160
  Installing       : perl-Pod-Checker-4:1.74-4.el9.noarch                                          102/160
  Installing       : perl-PerlIO-via-QuotedPrint-0.09-4.el9.noarch                                 103/160
  Installing       : perl-Package-Generator-1.106-23.el9.noarch                                    104/160
  Installing       : perl-Sub-Exporter-0.987-27.el9.noarch                                         105/160
  Installing       : perl-Object-HashBase-0.009-7.el9.noarch                                       106/160
  Installing       : perl-ODBM_File-1.16-483.el9.x86_64                                            107/160
  Installing       : perl-Net-1.02-483.el9.noarch                                                  108/160
  Installing       : perl-NEXT-0.67-483.el9.noarch                                                 109/160
  Installing       : perl-Module-Loaded-1:0.08-483.el9.noarch                                      110/160
  Installing       : perl-Memoize-1.03-483.el9.noarch                                              111/160
  Installing       : perl-Math-BigInt-FastCalc-0.500.900-460.el9.x86_64                            112/160
  Installing       : perl-MRO-Compat-0.13-15.el9.noarch                                            113/160
  Installing       : perl-Data-Section-0.200007-14.el9.noarch                                      114/160
  Installing       : perl-Software-License-0.103014-12.el9.noarch                                  115/160
  Installing       : perl-MIME-Charset-1.012.2-15.el9.noarch                                       116/160
  Installing       : perl-Unicode-LineBreak-2019.001-11.el9.x86_64                                 117/160
  Installing       : perl-Importer-0.026-4.el9.noarch                                              118/160
  Installing       : perl-Term-Table-0.015-8.el9.noarch                                            119/160
  Installing       : perl-Test-Simple-3:1.302183-4.el9.noarch                                      120/160
  Installing       : perl-IPC-System-Simple-1.30-6.el9.noarch                                      121/160
  Installing       : perl-autodie-2.34-4.el9.noarch                                                122/160
  Installing       : perl-IPC-SysV-2.09-4.el9.x86_64                                               123/160
  Installing       : perl-I18N-Collate-1.02-483.el9.noarch                                         124/160
  Installing       : perl-GDBM_File-1.18-483.el9.x86_64                                            125/160
  Installing       : perl-FindBin-1.51-483.el9.noarch                                              126/160
  Installing       : perl-FileCache-1.10-483.el9.noarch                                            127/160
  Installing       : perl-File-Which-1.23-10.el9.noarch                                            128/160
  Installing       : perl-File-HomeDir-1.006-4.el9.noarch                                          129/160
  Installing       : perl-File-DosGlob-1.12-483.el9.x86_64                                         130/160
  Installing       : perl-English-1.11-483.el9.noarch                                              131/160
  Installing       : perl-Digest-SHA1-2.13-34.el9.x86_64                                           132/160
  Installing       : perl-Devel-Size-0.83-10.el9.x86_64                                            133/160
  Installing       : perl-DB_File-1.855-4.el9.x86_64                                               134/160
  Installing       : perl-Config-Perl-V-0.33-4.el9.noarch                                          135/160
  Installing       : perl-Config-Extensions-0.03-483.el9.noarch                                    136/160
  Installing       : perl-Compress-Raw-Lzma-2.101-3.el9.x86_64                                     137/160
  Installing       : perl-IO-Compress-Lzma-2.101-4.el9.noarch                                      138/160
  Installing       : perl-Compress-Bzip2-2.28-5.el9.x86_64                                         139/160
  Installing       : perl-CPAN-DistnameInfo-0.12-23.el9.noarch                                     140/160
  Installing       : perl-Attribute-Handlers-1.01-483.el9.noarch                                   141/160
  Installing       : perl-Algorithm-Diff-1.2010-4.el9.noarch                                       142/160
  Installing       : perl-Text-Diff-1.45-13.el9.noarch                                             143/160
  Installing       : perl-Archive-Tar-2.38-6.el9.noarch                                            144/160
  Installing       : perl-Module-Signature-0.88-1.el9.noarch                                       145/160
  Installing       : python3-pyparsing-2.4.7-9.el9.noarch                                          146/160
  Installing       : systemtap-sdt-dtrace-5.4-4.el9.x86_64                                         147/160
  Installing       : systemtap-sdt-devel-5.4-4.el9.x86_64                                          148/160
  Installing       : perl-ExtUtils-Install-2.20-4.el9.noarch                                       149/160
  Installing       : perl-devel-4:5.32.1-483.el9.x86_64                                            150/160
  Installing       : perl-ExtUtils-MakeMaker-2:7.60-3.el9.noarch                                   151/160
  Installing       : perl-ExtUtils-CBuilder-1:0.280236-5.el9.noarch                                152/160
  Installing       : perl-ExtUtils-Embed-1.35-483.el9.noarch                                       153/160
  Installing       : perl-ExtUtils-Miniperl-1.09-483.el9.noarch                                    154/160
  Installing       : perl-libnetcfg-4:5.32.1-483.el9.noarch                                        155/160
  Installing       : perl-Encode-devel-4:3.08-462.el9.x86_64                                       156/160
  Installing       : perl-inc-latest-2:0.500-20.el9.noarch                                         157/160
  Installing       : perl-Module-Build-2:0.42.31-9.el9.noarch                                      158/160
  Installing       : perl-CPAN-2.29-5.el9.noarch                                                   159/160
  Installing       : perl-4:5.32.1-483.el9.x86_64                                                  160/160
  Running scriptlet: perl-4:5.32.1-483.el9.x86_64                                                  160/160
  Verifying        : python3-pyparsing-2.4.7-9.el9.noarch                                            1/160
  Verifying        : perl-4:5.32.1-483.el9.x86_64                                                    2/160
  Verifying        : perl-Algorithm-Diff-1.2010-4.el9.noarch                                         3/160
  Verifying        : perl-Archive-Tar-2.38-6.el9.noarch                                              4/160
  Verifying        : perl-Archive-Zip-1.68-6.el9.noarch                                              5/160
  Verifying        : perl-Attribute-Handlers-1.01-483.el9.noarch                                     6/160
  Verifying        : perl-AutoSplit-5.74-483.el9.noarch                                              7/160
  Verifying        : perl-Benchmark-1.23-483.el9.noarch                                              8/160
  Verifying        : perl-CPAN-2.29-5.el9.noarch                                                     9/160
  Verifying        : perl-CPAN-DistnameInfo-0.12-23.el9.noarch                                      10/160
  Verifying        : perl-CPAN-Meta-2.150010-460.el9.noarch                                         11/160
  Verifying        : perl-CPAN-Meta-Requirements-2.140-461.el9.noarch                               12/160
  Verifying        : perl-CPAN-Meta-YAML-0.018-461.el9.noarch                                       13/160
  Verifying        : perl-Compress-Bzip2-2.28-5.el9.x86_64                                          14/160
  Verifying        : perl-Compress-Raw-Bzip2-2.101-5.el9.x86_64                                     15/160
  Verifying        : perl-Compress-Raw-Lzma-2.101-3.el9.x86_64                                      16/160
  Verifying        : perl-Compress-Raw-Zlib-2.101-5.el9.x86_64                                      17/160
  Verifying        : perl-Config-Extensions-0.03-483.el9.noarch                                     18/160
  Verifying        : perl-Config-Perl-V-0.33-4.el9.noarch                                           19/160
  Verifying        : perl-DBM_Filter-0.06-483.el9.noarch                                            20/160
  Verifying        : perl-DB_File-1.855-4.el9.x86_64                                                21/160
  Verifying        : perl-Data-OptList-0.110-17.el9.noarch                                          22/160
  Verifying        : perl-Data-Section-0.200007-14.el9.noarch                                       23/160
  Verifying        : perl-Devel-PPPort-3.62-4.el9.x86_64                                            24/160
  Verifying        : perl-Devel-Peek-1.28-483.el9.x86_64                                            25/160
  Verifying        : perl-Devel-SelfStubber-1.06-483.el9.noarch                                     26/160
  Verifying        : perl-Devel-Size-0.83-10.el9.x86_64                                             27/160
  Verifying        : perl-Digest-SHA-1:6.02-461.el9.x86_64                                          28/160
  Verifying        : perl-Digest-SHA1-2.13-34.el9.x86_64                                            29/160
  Verifying        : perl-DirHandle-1.05-483.el9.noarch                                             30/160
  Verifying        : perl-Dumpvalue-2.27-483.el9.noarch                                             31/160
  Verifying        : perl-Encode-Locale-1.05-21.el9.noarch                                          32/160
  Verifying        : perl-Encode-devel-4:3.08-462.el9.x86_64                                        33/160
  Verifying        : perl-English-1.11-483.el9.noarch                                               34/160
  Verifying        : perl-Env-1.04-460.el9.noarch                                                   35/160
  Verifying        : perl-ExtUtils-CBuilder-1:0.280236-5.el9.noarch                                 36/160
  Verifying        : perl-ExtUtils-Command-2:7.60-3.el9.noarch                                      37/160
  Verifying        : perl-ExtUtils-Constant-0.25-483.el9.noarch                                     38/160
  Verifying        : perl-ExtUtils-Embed-1.35-483.el9.noarch                                        39/160
  Verifying        : perl-ExtUtils-Install-2.20-4.el9.noarch                                        40/160
  Verifying        : perl-ExtUtils-MM-Utils-2:7.60-3.el9.noarch                                     41/160
  Verifying        : perl-ExtUtils-MakeMaker-2:7.60-3.el9.noarch                                    42/160
  Verifying        : perl-ExtUtils-Manifest-1:1.73-4.el9.noarch                                     43/160
  Verifying        : perl-ExtUtils-Miniperl-1.09-483.el9.noarch                                     44/160
  Verifying        : perl-ExtUtils-ParseXS-1:3.40-460.el9.noarch                                    45/160
  Verifying        : perl-File-DosGlob-1.12-483.el9.x86_64                                          46/160
  Verifying        : perl-File-Fetch-1.00-4.el9.noarch                                              47/160
  Verifying        : perl-File-HomeDir-1.006-4.el9.noarch                                           48/160
  Verifying        : perl-File-Which-1.23-10.el9.noarch                                             49/160
  Verifying        : perl-FileCache-1.10-483.el9.noarch                                             50/160
  Verifying        : perl-Filter-2:1.60-4.el9.x86_64                                                51/160
  Verifying        : perl-Filter-Simple-0.96-460.el9.noarch                                         52/160
  Verifying        : perl-FindBin-1.51-483.el9.noarch                                               53/160
  Verifying        : perl-GDBM_File-1.18-483.el9.x86_64                                             54/160
  Verifying        : perl-Hash-Util-0.23-483.el9.x86_64                                             55/160
  Verifying        : perl-Hash-Util-FieldHash-1.20-483.el9.x86_64                                   56/160
  Verifying        : perl-I18N-Collate-1.02-483.el9.noarch                                          57/160
  Verifying        : perl-I18N-LangTags-0.44-483.el9.noarch                                         58/160
  Verifying        : perl-I18N-Langinfo-0.19-483.el9.x86_64                                         59/160
  Verifying        : perl-IO-Compress-2.102-4.el9.noarch                                            60/160
  Verifying        : perl-IO-Compress-Lzma-2.101-4.el9.noarch                                       61/160
  Verifying        : perl-IO-Zlib-1:1.11-4.el9.noarch                                               62/160
  Verifying        : perl-IPC-Cmd-2:1.04-461.el9.noarch                                             63/160
  Verifying        : perl-IPC-SysV-2.09-4.el9.x86_64                                                64/160
  Verifying        : perl-IPC-System-Simple-1.30-6.el9.noarch                                       65/160
  Verifying        : perl-Importer-0.026-4.el9.noarch                                               66/160
  Verifying        : perl-JSON-PP-1:4.06-4.el9.noarch                                               67/160
  Verifying        : perl-Locale-Maketext-1.29-461.el9.noarch                                       68/160
  Verifying        : perl-Locale-Maketext-Simple-1:0.21-483.el9.noarch                              69/160
  Verifying        : perl-MIME-Charset-1.012.2-15.el9.noarch                                        70/160
  Verifying        : perl-MRO-Compat-0.13-15.el9.noarch                                             71/160
  Verifying        : perl-Math-BigInt-FastCalc-0.500.900-460.el9.x86_64                             72/160
  Verifying        : perl-Math-BigRat-0.2614-460.el9.noarch                                         73/160
  Verifying        : perl-Memoize-1.03-483.el9.noarch                                               74/160
  Verifying        : perl-Module-Build-2:0.42.31-9.el9.noarch                                       75/160
  Verifying        : perl-Module-CoreList-1:5.20240609-1.el9.noarch                                 76/160
  Verifying        : perl-Module-CoreList-tools-1:5.20240609-1.el9.noarch                           77/160
  Verifying        : perl-Module-Load-1:0.36-4.el9.noarch                                           78/160
  Verifying        : perl-Module-Load-Conditional-0.74-4.el9.noarch                                 79/160
  Verifying        : perl-Module-Loaded-1:0.08-483.el9.noarch                                       80/160
  Verifying        : perl-Module-Metadata-1.000037-460.el9.noarch                                   81/160
  Verifying        : perl-Module-Signature-0.88-1.el9.noarch                                        82/160
  Verifying        : perl-NEXT-0.67-483.el9.noarch                                                  83/160
  Verifying        : perl-Net-1.02-483.el9.noarch                                                   84/160
  Verifying        : perl-Net-Ping-2.74-5.el9.noarch                                                85/160
  Verifying        : perl-ODBM_File-1.16-483.el9.x86_64                                             86/160
  Verifying        : perl-Object-HashBase-0.009-7.el9.noarch                                        87/160
  Verifying        : perl-Opcode-1.48-483.el9.x86_64                                                88/160
  Verifying        : perl-Package-Generator-1.106-23.el9.noarch                                     89/160
  Verifying        : perl-Params-Check-1:0.38-461.el9.noarch                                        90/160
  Verifying        : perl-Params-Util-1.102-5.el9.x86_64                                            91/160
  Verifying        : perl-Perl-OSType-1.010-461.el9.noarch                                          92/160
  Verifying        : perl-PerlIO-via-QuotedPrint-0.09-4.el9.noarch                                  93/160
  Verifying        : perl-Pod-Checker-4:1.74-4.el9.noarch                                           94/160
  Verifying        : perl-Pod-Functions-1.13-483.el9.noarch                                         95/160
  Verifying        : perl-Pod-Html-1.25-483.el9.noarch                                              96/160
  Verifying        : perl-Safe-2.41-483.el9.noarch                                                  97/160
  Verifying        : perl-Search-Dict-1.07-483.el9.noarch                                           98/160
  Verifying        : perl-SelfLoader-1.26-483.el9.noarch                                            99/160
  Verifying        : perl-Software-License-0.103014-12.el9.noarch                                  100/160
  Verifying        : perl-Sub-Exporter-0.987-27.el9.noarch                                         101/160
  Verifying        : perl-Sub-Install-0.928-28.el9.noarch                                          102/160
  Verifying        : perl-Sys-Hostname-1.23-483.el9.x86_64                                         103/160
  Verifying        : perl-Sys-Syslog-0.36-461.el9.x86_64                                           104/160
  Verifying        : perl-Term-Complete-1.403-483.el9.noarch                                       105/160
  Verifying        : perl-Term-ReadLine-1.17-483.el9.noarch                                        106/160
  Verifying        : perl-Term-Size-Any-0.002-35.el9.noarch                                        107/160
  Verifying        : perl-Term-Size-Perl-0.031-12.el9.x86_64                                       108/160
  Verifying        : perl-Term-Table-0.015-8.el9.noarch                                            109/160
  Verifying        : perl-Test-1.31-483.el9.noarch                                                 110/160
  Verifying        : perl-Test-Harness-1:3.42-461.el9.noarch                                       111/160
  Verifying        : perl-Test-Simple-3:1.302183-4.el9.noarch                                      112/160
  Verifying        : perl-Text-Abbrev-1.02-483.el9.noarch                                          113/160
  Verifying        : perl-Text-Balanced-2.04-4.el9.noarch                                          114/160
  Verifying        : perl-Text-Diff-1.45-13.el9.noarch                                             115/160
  Verifying        : perl-Text-Glob-0.11-15.el9.noarch                                             116/160
  Verifying        : perl-Text-Template-1.59-5.el9.noarch                                          117/160
  Verifying        : perl-Thread-3.05-483.el9.noarch                                               118/160
  Verifying        : perl-Thread-Semaphore-2.13-483.el9.noarch                                     119/160
  Verifying        : perl-Tie-4.6-483.el9.noarch                                                   120/160
  Verifying        : perl-Tie-File-1.06-483.el9.noarch                                             121/160
  Verifying        : perl-Tie-Memoize-1.1-483.el9.noarch                                           122/160
  Verifying        : perl-Tie-RefHash-1.40-4.el9.noarch                                            123/160
  Verifying        : perl-Time-1.03-483.el9.noarch                                                 124/160
  Verifying        : perl-Time-HiRes-4:1.9764-462.el9.x86_64                                       125/160
  Verifying        : perl-Time-Piece-1.3401-483.el9.x86_64                                         126/160
  Verifying        : perl-Unicode-Collate-1.29-4.el9.x86_64                                        127/160
  Verifying        : perl-Unicode-LineBreak-2019.001-11.el9.x86_64                                 128/160
  Verifying        : perl-Unicode-Normalize-1.27-461.el9.x86_64                                    129/160
  Verifying        : perl-Unicode-UCD-0.75-483.el9.noarch                                          130/160
  Verifying        : perl-User-pwent-1.03-483.el9.noarch                                           131/160
  Verifying        : perl-autodie-2.34-4.el9.noarch                                                132/160
  Verifying        : perl-autouse-1.11-483.el9.noarch                                              133/160
  Verifying        : perl-bignum-0.51-460.el9.noarch                                               134/160
  Verifying        : perl-blib-1.07-483.el9.noarch                                                 135/160
  Verifying        : perl-debugger-1.56-483.el9.noarch                                             136/160
  Verifying        : perl-deprecate-0.04-483.el9.noarch                                            137/160
  Verifying        : perl-devel-4:5.32.1-483.el9.x86_64                                            138/160
  Verifying        : perl-diagnostics-1.37-483.el9.noarch                                          139/160
  Verifying        : perl-doc-5.32.1-483.el9.noarch                                                140/160
  Verifying        : perl-encoding-4:3.00-462.el9.x86_64                                           141/160
  Verifying        : perl-encoding-warnings-0.13-483.el9.noarch                                    142/160
  Verifying        : perl-experimental-0.022-6.el9.noarch                                          143/160
  Verifying        : perl-fields-2.27-483.el9.noarch                                               144/160
  Verifying        : perl-filetest-1.03-483.el9.noarch                                             145/160
  Verifying        : perl-inc-latest-2:0.500-20.el9.noarch                                         146/160
  Verifying        : perl-less-0.03-483.el9.noarch                                                 147/160
  Verifying        : perl-libnetcfg-4:5.32.1-483.el9.noarch                                        148/160
  Verifying        : perl-local-lib-2.000024-13.el9.noarch                                         149/160
  Verifying        : perl-meta-notation-5.32.1-483.el9.noarch                                      150/160
  Verifying        : perl-open-1.12-483.el9.noarch                                                 151/160
  Verifying        : perl-perlfaq-5.20210520-1.el9.noarch                                          152/160
  Verifying        : perl-ph-5.32.1-483.el9.x86_64                                                 153/160
  Verifying        : perl-sigtrap-1.09-483.el9.noarch                                              154/160
  Verifying        : perl-sort-2.04-483.el9.noarch                                                 155/160
  Verifying        : perl-utils-5.32.1-483.el9.noarch                                              156/160
  Verifying        : perl-vmsish-1.04-483.el9.noarch                                               157/160
  Verifying        : sombok-2.4.0-16.el9.x86_64                                                    158/160
  Verifying        : systemtap-sdt-devel-5.4-4.el9.x86_64                                          159/160
  Verifying        : systemtap-sdt-dtrace-5.4-4.el9.x86_64                                         160/160

Installed:
  perl-4:5.32.1-483.el9.x86_64                        perl-Algorithm-Diff-1.2010-4.el9.noarch
  perl-Archive-Tar-2.38-6.el9.noarch                  perl-Archive-Zip-1.68-6.el9.noarch
  perl-Attribute-Handlers-1.01-483.el9.noarch         perl-AutoSplit-5.74-483.el9.noarch
  perl-Benchmark-1.23-483.el9.noarch                  perl-CPAN-2.29-5.el9.noarch
  perl-CPAN-DistnameInfo-0.12-23.el9.noarch           perl-CPAN-Meta-2.150010-460.el9.noarch
  perl-CPAN-Meta-Requirements-2.140-461.el9.noarch    perl-CPAN-Meta-YAML-0.018-461.el9.noarch
  perl-Compress-Bzip2-2.28-5.el9.x86_64               perl-Compress-Raw-Bzip2-2.101-5.el9.x86_64
  perl-Compress-Raw-Lzma-2.101-3.el9.x86_64           perl-Compress-Raw-Zlib-2.101-5.el9.x86_64
  perl-Config-Extensions-0.03-483.el9.noarch          perl-Config-Perl-V-0.33-4.el9.noarch
  perl-DBM_Filter-0.06-483.el9.noarch                 perl-DB_File-1.855-4.el9.x86_64
  perl-Data-OptList-0.110-17.el9.noarch               perl-Data-Section-0.200007-14.el9.noarch
  perl-Devel-PPPort-3.62-4.el9.x86_64                 perl-Devel-Peek-1.28-483.el9.x86_64
  perl-Devel-SelfStubber-1.06-483.el9.noarch          perl-Devel-Size-0.83-10.el9.x86_64
  perl-Digest-SHA-1:6.02-461.el9.x86_64               perl-Digest-SHA1-2.13-34.el9.x86_64
  perl-DirHandle-1.05-483.el9.noarch                  perl-Dumpvalue-2.27-483.el9.noarch
  perl-Encode-Locale-1.05-21.el9.noarch               perl-Encode-devel-4:3.08-462.el9.x86_64
  perl-English-1.11-483.el9.noarch                    perl-Env-1.04-460.el9.noarch
  perl-ExtUtils-CBuilder-1:0.280236-5.el9.noarch      perl-ExtUtils-Command-2:7.60-3.el9.noarch
  perl-ExtUtils-Constant-0.25-483.el9.noarch          perl-ExtUtils-Embed-1.35-483.el9.noarch
  perl-ExtUtils-Install-2.20-4.el9.noarch             perl-ExtUtils-MM-Utils-2:7.60-3.el9.noarch
  perl-ExtUtils-MakeMaker-2:7.60-3.el9.noarch         perl-ExtUtils-Manifest-1:1.73-4.el9.noarch
  perl-ExtUtils-Miniperl-1.09-483.el9.noarch          perl-ExtUtils-ParseXS-1:3.40-460.el9.noarch
  perl-File-DosGlob-1.12-483.el9.x86_64               perl-File-Fetch-1.00-4.el9.noarch
  perl-File-HomeDir-1.006-4.el9.noarch                perl-File-Which-1.23-10.el9.noarch
  perl-FileCache-1.10-483.el9.noarch                  perl-Filter-2:1.60-4.el9.x86_64
  perl-Filter-Simple-0.96-460.el9.noarch              perl-FindBin-1.51-483.el9.noarch
  perl-GDBM_File-1.18-483.el9.x86_64                  perl-Hash-Util-0.23-483.el9.x86_64
  perl-Hash-Util-FieldHash-1.20-483.el9.x86_64        perl-I18N-Collate-1.02-483.el9.noarch
  perl-I18N-LangTags-0.44-483.el9.noarch              perl-I18N-Langinfo-0.19-483.el9.x86_64
  perl-IO-Compress-2.102-4.el9.noarch                 perl-IO-Compress-Lzma-2.101-4.el9.noarch
  perl-IO-Zlib-1:1.11-4.el9.noarch                    perl-IPC-Cmd-2:1.04-461.el9.noarch
  perl-IPC-SysV-2.09-4.el9.x86_64                     perl-IPC-System-Simple-1.30-6.el9.noarch
  perl-Importer-0.026-4.el9.noarch                    perl-JSON-PP-1:4.06-4.el9.noarch
  perl-Locale-Maketext-1.29-461.el9.noarch            perl-Locale-Maketext-Simple-1:0.21-483.el9.noarch
  perl-MIME-Charset-1.012.2-15.el9.noarch             perl-MRO-Compat-0.13-15.el9.noarch
  perl-Math-BigInt-FastCalc-0.500.900-460.el9.x86_64  perl-Math-BigRat-0.2614-460.el9.noarch
  perl-Memoize-1.03-483.el9.noarch                    perl-Module-Build-2:0.42.31-9.el9.noarch
  perl-Module-CoreList-1:5.20240609-1.el9.noarch      perl-Module-CoreList-tools-1:5.20240609-1.el9.noarch
  perl-Module-Load-1:0.36-4.el9.noarch                perl-Module-Load-Conditional-0.74-4.el9.noarch
  perl-Module-Loaded-1:0.08-483.el9.noarch            perl-Module-Metadata-1.000037-460.el9.noarch
  perl-Module-Signature-0.88-1.el9.noarch             perl-NEXT-0.67-483.el9.noarch
  perl-Net-1.02-483.el9.noarch                        perl-Net-Ping-2.74-5.el9.noarch
  perl-ODBM_File-1.16-483.el9.x86_64                  perl-Object-HashBase-0.009-7.el9.noarch
  perl-Opcode-1.48-483.el9.x86_64                     perl-Package-Generator-1.106-23.el9.noarch
  perl-Params-Check-1:0.38-461.el9.noarch             perl-Params-Util-1.102-5.el9.x86_64
  perl-Perl-OSType-1.010-461.el9.noarch               perl-PerlIO-via-QuotedPrint-0.09-4.el9.noarch
  perl-Pod-Checker-4:1.74-4.el9.noarch                perl-Pod-Functions-1.13-483.el9.noarch
  perl-Pod-Html-1.25-483.el9.noarch                   perl-Safe-2.41-483.el9.noarch
  perl-Search-Dict-1.07-483.el9.noarch                perl-SelfLoader-1.26-483.el9.noarch
  perl-Software-License-0.103014-12.el9.noarch        perl-Sub-Exporter-0.987-27.el9.noarch
  perl-Sub-Install-0.928-28.el9.noarch                perl-Sys-Hostname-1.23-483.el9.x86_64
  perl-Sys-Syslog-0.36-461.el9.x86_64                 perl-Term-Complete-1.403-483.el9.noarch
  perl-Term-ReadLine-1.17-483.el9.noarch              perl-Term-Size-Any-0.002-35.el9.noarch
  perl-Term-Size-Perl-0.031-12.el9.x86_64             perl-Term-Table-0.015-8.el9.noarch
  perl-Test-1.31-483.el9.noarch                       perl-Test-Harness-1:3.42-461.el9.noarch
  perl-Test-Simple-3:1.302183-4.el9.noarch            perl-Text-Abbrev-1.02-483.el9.noarch
  perl-Text-Balanced-2.04-4.el9.noarch                perl-Text-Diff-1.45-13.el9.noarch
  perl-Text-Glob-0.11-15.el9.noarch                   perl-Text-Template-1.59-5.el9.noarch
  perl-Thread-3.05-483.el9.noarch                     perl-Thread-Semaphore-2.13-483.el9.noarch
  perl-Tie-4.6-483.el9.noarch                         perl-Tie-File-1.06-483.el9.noarch
  perl-Tie-Memoize-1.1-483.el9.noarch                 perl-Tie-RefHash-1.40-4.el9.noarch
  perl-Time-1.03-483.el9.noarch                       perl-Time-HiRes-4:1.9764-462.el9.x86_64
  perl-Time-Piece-1.3401-483.el9.x86_64               perl-Unicode-Collate-1.29-4.el9.x86_64
  perl-Unicode-LineBreak-2019.001-11.el9.x86_64       perl-Unicode-Normalize-1.27-461.el9.x86_64
  perl-Unicode-UCD-0.75-483.el9.noarch                perl-User-pwent-1.03-483.el9.noarch
  perl-autodie-2.34-4.el9.noarch                      perl-autouse-1.11-483.el9.noarch
  perl-bignum-0.51-460.el9.noarch                     perl-blib-1.07-483.el9.noarch
  perl-debugger-1.56-483.el9.noarch                   perl-deprecate-0.04-483.el9.noarch
  perl-devel-4:5.32.1-483.el9.x86_64                  perl-diagnostics-1.37-483.el9.noarch
  perl-doc-5.32.1-483.el9.noarch                      perl-encoding-4:3.00-462.el9.x86_64
  perl-encoding-warnings-0.13-483.el9.noarch          perl-experimental-0.022-6.el9.noarch
  perl-fields-2.27-483.el9.noarch                     perl-filetest-1.03-483.el9.noarch
  perl-inc-latest-2:0.500-20.el9.noarch               perl-less-0.03-483.el9.noarch
  perl-libnetcfg-4:5.32.1-483.el9.noarch              perl-local-lib-2.000024-13.el9.noarch
  perl-meta-notation-5.32.1-483.el9.noarch            perl-open-1.12-483.el9.noarch
  perl-perlfaq-5.20210520-1.el9.noarch                perl-ph-5.32.1-483.el9.x86_64
  perl-sigtrap-1.09-483.el9.noarch                    perl-sort-2.04-483.el9.noarch
  perl-utils-5.32.1-483.el9.noarch                    perl-vmsish-1.04-483.el9.noarch
  python3-pyparsing-2.4.7-9.el9.noarch                sombok-2.4.0-16.el9.x86_64
  systemtap-sdt-devel-5.4-4.el9.x86_64                systemtap-sdt-dtrace-5.4-4.el9.x86_64

Complete!
[root@192 SOURCES]# rpmbuild -tb httpd-2.4.62.tar.bz2
......

Executing(%clean): /bin/sh -e /var/tmp/rpm-tmp.Wh8u26
+ umask 022
+ cd /root/rpmbuild/BUILD
+ cd httpd-2.4.62
+ rm -rf /root/rpmbuild/BUILDROOT/httpd-2.4.62-1.x86_64
+ RPM_EC=0
++ jobs -p
+ exit 0
# 5. Проверка и настройка опций. Редактирование .spec файл
[root@192 SOURCES]# tar -xjf httpd-2.4.62.tar.bz2 -C /tmp
[root@192 SOURCES]# cp /tmp/httpd-2.4.62/httpd.spec ~/rpmbuild/SPECS/
# Редактируем файл .spec файл
[root@192 SOURCES]# sudo nano  ~/rpmbuild/SPECS/httpd-minimal.spec
spec
Name:           httpd-custom
Version:        2.4.62
Release:        1%{?dist}
Summary:        Custom Apache HTTP Server

%define debug_package %{nil}

License:        Apache 2.0
URL:            https://httpd.apache.org/
Source0:        httpd-%{version}.tar.bz2

BuildRequires:  gcc, make, pcre-devel, openssl-devel, apr-devel, apr-util-devel

%description
Custom build of Apache HTTP Server with additional modules.

%prep
%setup -q -n httpd-%{version}

%build
./configure --prefix=/usr/local/apache2 \
            --enable-rewrite \
            --enable-ssl \
            --enable-so \
            --enable-mods-shared=all
make %{?_smp_mflags}

%install
rm -rf %{buildroot}
make install DESTDIR=%{buildroot}

%files
%defattr(-,root,root,-)
/usr/local/apache2

%changelog
* Mon Apr 26 2025 Your Name <email@example.com> - 2.4.62-1
- Initial custom build
[root@192 SPECS]# rpmbuild -ba ~/rpmbuild/SPECS/httpd-minimal.spec
Executing(%clean): /bin/sh -e /var/tmp/rpm-tmp.a8VaQf
+ umask 022
+ cd /root/rpmbuild/BUILD
+ cd httpd-2.4.62
+ rm -rf /root/rpmbuild/BUILDROOT/httpd-custom-2.4.62-1.el9.x86_64
+ RPM_EC=0
++ jobs -p
+ exit 0
[root@192 SPECS]# ls -la ~/rpmbuild/RPMS/x86_64/
total 6148
drwxr-xr-x. 2 root root    4096 Apr 26 22:08 .
drwxr-xr-x. 3 root root      20 Apr 26 20:52 ..
-rw-r--r--. 1 root root 5539171 Apr 26 22:08 httpd-custom-2.4.62-1.el9.x86_64.rpm
-rw-r--r--. 1 root root   57113 Apr 26 20:53 mod_authnz_ldap-2.4.62-1.x86_64.rpm
-rw-r--r--. 1 root root   88693 Apr 26 20:53 mod_authnz_ldap-debuginfo-2.4.62-1.x86_64.rpm
-rw-r--r--. 1 root root   56273 Apr 26 20:53 mod_lua-2.4.62-1.x86_64.rpm
-rw-r--r--. 1 root root  126452 Apr 26 20:53 mod_lua-debuginfo-2.4.62-1.x86_64.rpm
-rw-r--r--. 1 root root   31483 Apr 26 20:53 mod_proxy_html-2.4.62-1.x86_64.rpm
-rw-r--r--. 1 root root   57109 Apr 26 20:53 mod_proxy_html-debuginfo-2.4.62-1.x86_64.rpm
-rw-r--r--. 1 root root  108566 Apr 26 20:53 mod_ssl-2.4.62-1.x86_64.rpm
-rw-r--r--. 1 root root  216923 Apr 26 20:53 mod_ssl-debuginfo-2.4.62-1.x86_64.rpm
# 6. Установка пакета
[root@192 SPECS]# sudo dnf localinstall ~/rpmbuild/RPMS/x86_64/httpd-custom-2.4.62-1.el9.x86_64.rpm
Last metadata expiration check: 1:51:07 ago on Sun 26 Apr 2026 08:25:03 PM MSK.
Dependencies resolved.
===========================================================================================================
 Package                   Architecture        Version                     Repository                 Size
===========================================================================================================
Installing:
 httpd-custom              x86_64              2.4.62-1.el9                @commandline              5.3 M

Transaction Summary
===========================================================================================================
Install  1 Package

Total size: 5.3 M
Installed size: 29 M
Is this ok [y/N]: y
Downloading Packages:
Running transaction check
Transaction check succeeded.
Running transaction test
Transaction test succeeded.
Running transaction
  Preparing        :                                                                                   1/1
  Installing       : httpd-custom-2.4.62-1.el9.x86_64                                                  1/1
  Running scriptlet: httpd-custom-2.4.62-1.el9.x86_64                                                  1/1
  Verifying        : httpd-custom-2.4.62-1.el9.x86_64                                                  1/1

Installed:
  httpd-custom-2.4.62-1.el9.x86_64

Complete!
# Проверяем что файлы установлены
[root@192 SPECS]# ls -la /usr/local/apache2/
total 52
drwxr-xr-x. 15 root root   175 Apr 26 22:16 .
drwxr-xr-x. 13 root root   146 Apr 26 22:16 ..
drwxr-xr-x.  2 root root  4096 Apr 26 22:16 bin
drwxr-xr-x.  2 root root   167 Apr 26 22:16 build
drwxr-xr-x.  2 root root    78 Apr 26 22:16 cgi-bin
drwxr-xr-x.  4 root root    84 Apr 26 22:16 conf
drwxr-xr-x.  3 root root  4096 Apr 26 22:16 error
drwxr-xr-x.  2 root root    24 Apr 26 22:16 htdocs
drwxr-xr-x.  3 root root  8192 Apr 26 22:16 icons
drwxr-xr-x.  2 root root  4096 Apr 26 22:16 include
drwxr-xr-x.  2 root root     6 Apr 26 22:07 logs
drwxr-xr-x.  4 root root    30 Apr 26 22:16 man
drwxr-xr-x. 14 root root 12288 Apr 26 22:16 manual
drwxr-xr-x.  2 root root  8192 Apr 26 22:16 modules
drwxr-xr-x.  2 root root     6 Apr 26 22:07 run
[root@192 SPECS]# ls -la /usr/local/apache2/bin/
total 1332
drwxr-xr-x.  2 root root   4096 Apr 26 22:16 .
drwxr-xr-x. 15 root root    175 Apr 26 22:16 ..
-rwxr-xr-x.  1 root root  77984 Apr 26 22:07 ab
-rwxr-xr-x.  1 root root   3441 Apr 26 22:05 apachectl
-rwxr-xr-x.  1 root root  23879 Apr 26 22:05 apxs
-rwxr-xr-x.  1 root root  17496 Apr 26 22:07 checkgid
-rwxr-xr-x.  1 root root   8874 Apr 26 22:05 dbmmanage
-rw-r--r--.  1 root root   1073 Apr 26 22:05 envvars
-rw-r--r--.  1 root root   1073 Apr 26 22:05 envvars-std
-rwxr-xr-x.  1 root root  18528 Apr 26 22:07 fcgistarter
-rwxr-xr-x.  1 root root  45656 Apr 26 22:07 htcacheclean
-rwxr-xr-x.  1 root root  32736 Apr 26 22:07 htdbm
-rwxr-xr-x.  1 root root  18808 Apr 26 22:07 htdigest
-rwxr-xr-x.  1 root root  32192 Apr 26 22:07 htpasswd
-rwxr-xr-x.  1 root root 975256 Apr 26 22:07 httpd
-rwxr-xr-x.  1 root root  18488 Apr 26 22:07 httxt2dbm
-rwxr-xr-x.  1 root root  19120 Apr 26 22:07 logresolve
-rwxr-xr-x.  1 root root  32120 Apr 26 22:07 rotatelogs
[root@192 SPECS]# ls -la /usr/local/apache2/modules/
total 4612
drwxr-xr-x.  2 root root   8192 Apr 26 22:16 .
drwxr-xr-x. 15 root root    175 Apr 26 22:16 ..
-rw-r--r--.  1 root root  17461 Apr 26 22:05 httpd.exp
-rwxr-xr-x.  1 root root  17424 Apr 26 22:07 mod_access_compat.so
-rwxr-xr-x.  1 root root  17168 Apr 26 22:07 mod_actions.so
-rwxr-xr-x.  1 root root  30608 Apr 26 22:07 mod_alias.so
-rwxr-xr-x.  1 root root  16792 Apr 26 22:07 mod_allowmethods.so
-rwxr-xr-x.  1 root root  16896 Apr 26 22:07 mod_asis.so
-rwxr-xr-x.  1 root root  21896 Apr 26 22:07 mod_auth_basic.so
-rwxr-xr-x.  1 root root  50064 Apr 26 22:07 mod_auth_digest.so
-rwxr-xr-x.  1 root root  44336 Apr 26 22:07 mod_auth_form.so
-rwxr-xr-x.  1 root root  16872 Apr 26 22:07 mod_authn_anon.so
-rwxr-xr-x.  1 root root  18032 Apr 26 22:07 mod_authn_core.so
-rwxr-xr-x.  1 root root  17688 Apr 26 22:07 mod_authn_dbd.so
-rwxr-xr-x.  1 root root  17272 Apr 26 22:07 mod_authn_dbm.so
-rwxr-xr-x.  1 root root  17112 Apr 26 22:07 mod_authn_file.so
-rwxr-xr-x.  1 root root  31240 Apr 26 22:07 mod_authn_socache.so
-rwxr-xr-x.  1 root root  86432 Apr 26 22:07 mod_authnz_ldap.so
-rwxr-xr-x.  1 root root  35952 Apr 26 22:07 mod_authz_core.so
-rwxr-xr-x.  1 root root  22248 Apr 26 22:07 mod_authz_dbd.so
-rwxr-xr-x.  1 root root  17648 Apr 26 22:07 mod_authz_dbm.so
-rwxr-xr-x.  1 root root  22024 Apr 26 22:07 mod_authz_groupfile.so
-rwxr-xr-x.  1 root root  22104 Apr 26 22:07 mod_authz_host.so
-rwxr-xr-x.  1 root root  16872 Apr 26 22:07 mod_authz_owner.so
-rwxr-xr-x.  1 root root  16944 Apr 26 22:07 mod_authz_user.so
-rwxr-xr-x.  1 root root  53456 Apr 26 22:07 mod_autoindex.so
-rwxr-xr-x.  1 root root  17336 Apr 26 22:07 mod_buffer.so
-rwxr-xr-x.  1 root root  52832 Apr 26 22:07 mod_cache_disk.so
-rwxr-xr-x.  1 root root 110496 Apr 26 22:07 mod_cache.so
-rwxr-xr-x.  1 root root  53136 Apr 26 22:07 mod_cache_socache.so
-rwxr-xr-x.  1 root root  61224 Apr 26 22:07 mod_cgid.so
-rwxr-xr-x.  1 root root  30768 Apr 26 22:07 mod_charset_lite.so
-rwxr-xr-x.  1 root root  17376 Apr 26 22:07 mod_data.so
-rwxr-xr-x.  1 root root  74104 Apr 26 22:07 mod_dav_fs.so
-rwxr-xr-x.  1 root root  27064 Apr 26 22:07 mod_dav_lock.so
-rwxr-xr-x.  1 root root 148024 Apr 26 22:07 mod_dav.so
-rwxr-xr-x.  1 root root  35704 Apr 26 22:07 mod_dbd.so
-rwxr-xr-x.  1 root root  56688 Apr 26 22:07 mod_deflate.so
-rwxr-xr-x.  1 root root  17752 Apr 26 22:07 mod_dialup.so
-rwxr-xr-x.  1 root root  17648 Apr 26 22:07 mod_dir.so
-rwxr-xr-x.  1 root root  21264 Apr 26 22:07 mod_dumpio.so
-rwxr-xr-x.  1 root root  17408 Apr 26 22:07 mod_echo.so
-rwxr-xr-x.  1 root root  17200 Apr 26 22:07 mod_env.so
-rwxr-xr-x.  1 root root  17872 Apr 26 22:07 mod_expires.so
-rwxr-xr-x.  1 root root  36360 Apr 26 22:07 mod_ext_filter.so
-rwxr-xr-x.  1 root root  22168 Apr 26 22:07 mod_file_cache.so
-rwxr-xr-x.  1 root root  26352 Apr 26 22:07 mod_filter.so
-rwxr-xr-x.  1 root root  32488 Apr 26 22:07 mod_headers.so
-rwxr-xr-x.  1 root root  17472 Apr 26 22:07 mod_heartbeat.so
-rwxr-xr-x.  1 root root  40488 Apr 26 22:07 mod_heartmonitor.so
-rwxr-xr-x.  1 root root  75104 Apr 26 22:07 mod_include.so
-rwxr-xr-x.  1 root root  45960 Apr 26 22:07 mod_info.so
-rwxr-xr-x.  1 root root  16816 Apr 26 22:07 mod_lbmethod_bybusyness.so
-rwxr-xr-x.  1 root root  16816 Apr 26 22:07 mod_lbmethod_byrequests.so
-rwxr-xr-x.  1 root root  16816 Apr 26 22:07 mod_lbmethod_bytraffic.so
-rwxr-xr-x.  1 root root  26800 Apr 26 22:07 mod_lbmethod_heartbeat.so
-rwxr-xr-x.  1 root root 114880 Apr 26 22:07 mod_ldap.so
-rwxr-xr-x.  1 root root  47056 Apr 26 22:07 mod_log_config.so
-rwxr-xr-x.  1 root root  22440 Apr 26 22:07 mod_log_debug.so
-rwxr-xr-x.  1 root root  17840 Apr 26 22:07 mod_log_forensic.so
-rwxr-xr-x.  1 root root  17928 Apr 26 22:07 mod_logio.so
-rwxr-xr-x.  1 root root 184184 Apr 26 22:07 mod_lua.so
-rwxr-xr-x.  1 root root  26528 Apr 26 22:07 mod_macro.so
-rwxr-xr-x.  1 root root  39928 Apr 26 22:07 mod_mime_magic.so
-rwxr-xr-x.  1 root root  35104 Apr 26 22:07 mod_mime.so
-rwxr-xr-x.  1 root root  50000 Apr 26 22:07 mod_negotiation.so
-rwxr-xr-x.  1 root root  87112 Apr 26 22:07 mod_proxy_ajp.so
-rwxr-xr-x.  1 root root  83776 Apr 26 22:07 mod_proxy_balancer.so
-rwxr-xr-x.  1 root root  26336 Apr 26 22:07 mod_proxy_connect.so
-rwxr-xr-x.  1 root root  21512 Apr 26 22:07 mod_proxy_express.so
-rwxr-xr-x.  1 root root  49080 Apr 26 22:07 mod_proxy_fcgi.so
-rwxr-xr-x.  1 root root  17384 Apr 26 22:07 mod_proxy_fdpass.so
-rwxr-xr-x.  1 root root  70328 Apr 26 22:07 mod_proxy_ftp.so
-rwxr-xr-x.  1 root root  54280 Apr 26 22:07 mod_proxy_hcheck.so
-rwxr-xr-x.  1 root root  53672 Apr 26 22:07 mod_proxy_html.so
-rwxr-xr-x.  1 root root  66896 Apr 26 22:07 mod_proxy_http.so
-rwxr-xr-x.  1 root root  31656 Apr 26 22:07 mod_proxy_scgi.so
-rwxr-xr-x.  1 root root 228440 Apr 26 22:07 mod_proxy.so
-rwxr-xr-x.  1 root root  27328 Apr 26 22:07 mod_proxy_uwsgi.so
-rwxr-xr-x.  1 root root  34928 Apr 26 22:07 mod_proxy_wstunnel.so
-rwxr-xr-x.  1 root root  21664 Apr 26 22:07 mod_ratelimit.so
-rwxr-xr-x.  1 root root  17736 Apr 26 22:07 mod_reflector.so
-rwxr-xr-x.  1 root root  40000 Apr 26 22:07 mod_remoteip.so
-rwxr-xr-x.  1 root root  22568 Apr 26 22:07 mod_reqtimeout.so
-rwxr-xr-x.  1 root root  21944 Apr 26 22:07 mod_request.so
-rwxr-xr-x.  1 root root 103640 Apr 26 22:07 mod_rewrite.so
-rwxr-xr-x.  1 root root  61552 Apr 26 22:07 mod_sed.so
-rwxr-xr-x.  1 root root  17432 Apr 26 22:07 mod_session_cookie.so
-rwxr-xr-x.  1 root root  39616 Apr 26 22:07 mod_session_crypto.so
-rwxr-xr-x.  1 root root  22320 Apr 26 22:07 mod_session_dbd.so
-rwxr-xr-x.  1 root root  35792 Apr 26 22:07 mod_session.so
-rwxr-xr-x.  1 root root  22136 Apr 26 22:07 mod_setenvif.so
-rwxr-xr-x.  1 root root  17256 Apr 26 22:07 mod_slotmem_plain.so
-rwxr-xr-x.  1 root root  26680 Apr 26 22:07 mod_slotmem_shm.so
-rwxr-xr-x.  1 root root  22176 Apr 26 22:07 mod_socache_dbm.so
-rwxr-xr-x.  1 root root  21960 Apr 26 22:07 mod_socache_memcache.so
-rwxr-xr-x.  1 root root  21984 Apr 26 22:07 mod_socache_redis.so
-rwxr-xr-x.  1 root root  38672 Apr 26 22:07 mod_socache_shmcb.so
-rwxr-xr-x.  1 root root  22024 Apr 26 22:07 mod_speling.so
-rwxr-xr-x.  1 root root 384112 Apr 26 22:07 mod_ssl.so
-rwxr-xr-x.  1 root root  34896 Apr 26 22:07 mod_status.so
-rwxr-xr-x.  1 root root  30480 Apr 26 22:07 mod_substitute.so
-rwxr-xr-x.  1 root root  17336 Apr 26 22:07 mod_unique_id.so
-rwxr-xr-x.  1 root root  21968 Apr 26 22:07 mod_unixd.so
-rwxr-xr-x.  1 root root  17360 Apr 26 22:07 mod_userdir.so
-rwxr-xr-x.  1 root root  22016 Apr 26 22:07 mod_usertrack.so
-rwxr-xr-x.  1 root root  16952 Apr 26 22:07 mod_version.so
-rwxr-xr-x.  1 root root  17576 Apr 26 22:07 mod_vhost_alias.so
-rwxr-xr-x.  1 root root  31864 Apr 26 22:07 mod_watchdog.so
-rwxr-xr-x.  1 root root  39416 Apr 26 22:07 mod_xml2enc.so
# Проверяем версию
[root@192 SPECS]# /usr/local/apache2/bin/httpd -v
Server version: Apache/2.4.62 (Unix)
Server built:   Apr 26 2025 00:00:00
# 7. Создать systemd сервис
sudo cat > /etc/systemd/system/httpd-custom.service << 'EOF'
[Unit]
Description=Custom Apache HTTP Server
After=network.target

[Service]
Type=forking
ExecStart=/usr/local/apache2/bin/apachectl start
ExecReload=/usr/local/apache2/bin/apachectl graceful
ExecStop=/usr/local/apache2/bin/apachectl stop
PIDFile=/usr/local/apache2/logs/httpd.pid
User=root
Group=root

[Install]
WantedBy=multi-user.target
EOF
[root@192 SPECS]# sudo systemctl daemon-reload
[root@192 SPECS]# sudo systemctl start httpd-custom
[root@192 SPECS]# sudo systemctl enable httpd-custom
Created symlink /etc/systemd/system/multi-user.target.wants/httpd-custom.service → /etc/systemd/system/httpd-custom.service.
[root@192 SPECS]# sudo systemctl status httpd-custom
● httpd-custom.service - Custom Apache HTTP Server
     Loaded: loaded (/etc/systemd/system/httpd-custom.service; enabled; preset: disabled)
     Active: active (running) since Sun 2026-04-26 22:21:19 MSK; 20s ago
   Main PID: 233391 (httpd)
      Tasks: 82 (limit: 48735)
     Memory: 6.8M (peak: 7.1M)
        CPU: 142ms
     CGroup: /system.slice/httpd-custom.service
             ├─233391 /usr/local/apache2/bin/httpd -k start
             ├─233392 /usr/local/apache2/bin/httpd -k start
             ├─233393 /usr/local/apache2/bin/httpd -k start
             └─233394 /usr/local/apache2/bin/httpd -k start

Apr 26 22:21:14 192.168.1.8 systemd[1]: Starting Custom Apache HTTP Server...
Apr 26 22:21:19 192.168.1.8 systemd[1]: httpd-custom.service: Can't open PID file /usr/local/apache2/logs/>
Apr 26 22:21:19 192.168.1.8 systemd[1]: Started Custom Apache HTTP Server.
