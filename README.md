# Reverse-Engineering-list-to-read
Материалы для прочтения и изучения темы Reverse Engineering

# При поддержке
Telegram канала RAP ( Reverse | Assembler | PWN ) (https://t.me/ReverseAssemblerPWN)
Codeby.net (https://codeby.net)

# Ссылки
Доброго времени суток. Нашёл на GitHab интересный англоязычный список полезных ссылок по реверс-инжинирингу. Перевёл для себя, добавил картинок и решил поделиться. Оригинал (https://github.com/onethawt/reverseengineering-reading-list)

# Библиотека программ

IDA Pro: КОРОЛЬ IDA - это доступный в Windows, Linux или Mac OS X многопроцессорный дизассемблер и отладчик, который предлагает так много функций, что трудно описать их все. (https://www.hex-rays.com/products/ida/)

Ghidra: Ghidra-это фреймворк обратного инжиниринга программного обеспечения (SRE), созданный и поддерживаемый исследовательским директоратом Агентства национальной безопасности. Эта платформа включает в себя набор высококачественных инструментов анализа программного обеспечения высокого класса, которые позволяют пользователям анализировать скомпилированный код на различных платформах, включая Windows, Mac OS и Linux. Возможности включают в себя ассемблирование, дизассемблирование, декомпиляцию, графы и скрипты, а также сотни других функций. Ghidra поддерживает широкий спектр наборов инструкций процесса и исполняемых форматов и может выполняться как в пользовательском-интерактивном, так и в автоматическом режимах. Пользователи также могут разрабатывать свои собственные подключаемые компоненты Ghidorah и/или скрипты с использованием Java или Python. (https://github.com/NationalSecurityAgency/ghidra)

Binary Ninja: Платформа обратного инжиниринга. Она фокусируется на чистом и простом в использовании интерфейсе с мощным многопоточным анализом, построенным на пользовательском промежуточном языке, чтобы быстро адаптироваться к различным архитектурам, платформам и компиляторам. (https://binary.ninja/)

Capstone: Capstone - это легкий мультиплатформенный, мультиархитектурный фреймворк для разборки. "Наша цель - сделать Capstone идеальным дизассмеблером для двоичного анализа и реверса в сообществе информационной безопасности." - говорят разработчики. (http://www.capstone-engine.org/)

Hopper: Hopper инструмент обратного инжиниринга для OS X и Linux, который позволяет вам дизассемблировать и декомпилировать ваши 32/64-битные исполняемые файлы для Mac, Linux, Windows и iOS! Базируется на Capstone, может быть дополнен скриптами. (https://www.hopperapp.com/)

PeachPy: Портативный эффективный генератор ассемблерного кода на высокоуровневом языке Python. (https://github.com/Maratyszcza/PeachPy)

Radare2: Портативный фреймворк реверс-инжиниринга для дизассемблирования, отладки, форензики и т.д. Базируется на Capstone, может быть дополнен скриптами. (http://www.radare.org/)

Cutter - это бесплатный и открытый фреймворк для реверс-инжиниринга, работающий на базе radare2 с возможностью дополнения плагинами . Его цель-создание продвинутой, настраиваемой платформы для реверс-инжиниринга, сохраняя при этом пользовательский опыт. Cutter создан реверс инженерами для реверс инженеров. (https://github.com/radareorg/cutter)

x64dbg: Отладчик Windows с открытым исходным кодом x64/x32. Наследник OlyDbg. (http://x64dbg.com/)

re_lab: Портативная среда реверс-инжиниринга с использованием docker. (https://github.com/cboin/re_lab)

# Android

Offensive & Defensive Android Reverse Engineering (https://github.com/rednaga/training/tree/master/DEFCON23)

# Ассемблер / Дизассемблер

Анализ необычной прошивки (http://blog.ptsecurity.com/2015/07/best-reverser-write-up-analyzing.html)
Дизассемблирование ARM V7 архитектуры (https://drive.google.com/file/d/0B0l-Qo3D3sAoMEhkcFBFVzRiNEk/view)

UROBOROS - Reassembling Disassembling - инструмент, который может разбирать исполняемые файлы до такой степени, что сгенерированный код может быть собран обратно в рабочие двоичные файлы без ручного усилия. (https://www.usenix.org/conference/usenixsecurity15/technical-sessions/presentation/wang-shuai)

Основы

Reverse Engineering 101 Speaker Presentation (https://vimeo.com/6764570)
Reverse Engineering 101 - NYU: Poly 2010: Вступление к реверс-инжинирингу, данное в Нью-Йоркском университете Poly 4 октября 2010 года Ароном Портным и Питером Зильберманом. (https://prezi.com/a5tm-lf0879-/reverse-engineering-101-nyupoly-2010/)
Reverse Engineering 102 - NYU: Poly 2010: Введение в реверс-инжиниринг (день 2), Данное в Нью-Йоркском университете Poly 11 октября 2010 года Ароном Портным и Питером Зильберманом. (https://prezi.com/e5a2tumdqocj/reverse-engineering-102-nyupoly-2010/)
CTF полевое руководство (https://trailofbits.github.io/ctf/)

# Книги

Modern X86 Assembly Language Programming: 32-bit, 64-bit, SSE, and AVX: Основы программирования на ассемблере x86. Он фокусируется на аспектах набора инструкций x86, которые наиболее важны для разработки прикладного программного обеспечения. (https://vk.com/doc33930450_487876299?hash=cab91631761ded7e1f)

Practical Malware Analysis (https://www.amazon.com/Practical-Malware-Analysis-Hands-Dissecting/dp/1593272901): эта книга научит вас инструментам и методам, используемым профессиональными аналитиками. Используя эту книгу в качестве руководства, вы сможете безопасно анализировать, отлаживать и разбирать любое вредоносное программное обеспечение, которое попадется вам на пути. Перевод на русском. (https://codeby.net/resources/vskrytie-pokazhet-prakticheskij-analiz-vredonosnogo-po.170/)

Practical Reverse Engineering: Книга охватывает x86, x64 и ARM (первая книга, которая охватывает все три); руткиты и драйверы кода режима ядра Windows; методы защиты виртуальных машин и многое другое. Она предлагает систематический подход к материалу, с большим количеством практических упражнений и реальных примеров. (https://codeby.net/resources/practical-reverse-engineering-x86-x64-arm-windows-kernel-reversing-tools-and-obfuscation.147/)

Reversing: Secrets of Reverse Engineering: Начните с базового учебника по реверс-инжинирингу включающего в себя компьютерные внутренности, операционные системы и язык ассемблера, а затем обсудите различные области применения обратного инжиниринга, эта книга предоставляет читателям практические, глубокие методы для реверс-инжиниринга программного обеспечения. (https://codeby.net/resources/reversing-secrets-of-reverse-engineering.152/)

Reverse Engineering for Beginners: Эта электронная книга, доступная на английском и русском языках, является хорошим введением для начинающих. Затронуты многочисленные темы: Oracle RDBMS, Itanium, ключи защиты от копирования, LD_PRELOAD, переполнение стека, ELF, формат файла win32 PE, x86-64, критические разделы, системные вызовы, TLS, позиционно-независимый код (PIC), профильная оптимизация, C++ STL, OpenMP, win32 SEH. (https://grishnan.ru/media/uploads/reverse_engineering/re4b-ru.pdf)

The IDA Pro Book: The Unofficial Guide to the World's Most Popular Disassembler (https://codeby.net/resources/ida-pro-book.887/): Второе издание книги IDA Pro, названное создателем IDA Pro "глубоким, всеобъемлющим и точным", охватывает все, начиная с самых первых шагов и заканчивая передовыми методами автоматизации. Русский перевод. (https://yutewiyof.gitbook.io/intro-rev-ida-pro/)

# Структура данных

Digging For Data Structures (http://ben.ransford.org/srg/papers/cozzie--digging.pdf)

MemPick: High-Level Data Structure Detection in C/C++ Binaries (http://www.cs.vu.nl/~herbertb/papers/mempick_wcre13.pdf)

# Эксплуатация

Dismantling Megamos Crypto: Wirelessly Lockpicking a Vehicle Immobilizer (https://www.usenix.org/sites/default/files/sec15_supplement.pdf)

Memory Graph Approach for Program Data Introspection and Modification (http://software.imdea.org/~juanca/papers/sigpath_esorics14.pdf)

Remote Exploitation of an Unaltered Passenger Vehicle (http://illmatics.com/Remote%20Car%20Hacking.pdf)


# Набор команд

Intel® 64 and IA-32 Architectures Software Developer Manuals: В этих руководствах описываются архитектура и среда программирования архитектур Intel ® 64 и IA-32. (http://www.intel.com/content/www/us/en/processors/architectures-software-developer-manuals.html)

X86 Opcode and Instruction Reference: Эта ссылка предназначена для точного указания кода операции и набора инструкций (включая x86-64). Его основная цель-точное определение параметров и атрибутов инструкции. (http://ref.x86asm.net/)

JSON x86-64 Intel instruction set: Весь набор инструкций Intel x86-64 в машиночитаемом формате JSON до AVX-512. (https://github.com/astocko/json-x86-64)
X86-64 Reference: Получено из сентябрьской версии 2014 года руководства разработчика программного обеспечения для архитектур Intel ® 64 и IA-32, тома 2A и 2B. Использует интеллектуальный анализ PDF для создания ссылки из официальных документов Intel. (http://www.felixcloutier.com/x86/)

# Mac and iOS
iOS App Reverse Engineering: iOS App Reverse Engineering-это 1-я в мире книга очень подробно описывающая навыки реверс-инжиниринга для iOS App. (https://codeby.net/resources/ios-app-reverse-engineering.113/)

iOS Kernel Security (https://reverse.put.as/wp-content/uploads/2011/06/D1T2-Mark-Dowd-Tarjei-Mandt-iOS6-Security.pdf)

Jailbreaking Techniques (https://reverse.put.as/wp-content/uploads/2011/06/pod2g-jailbreak-techniques-wwjc-2012.pdf)

Reversing iOS Apps: A Practical Approach (https://s3.amazonaws.com/s3.synack.com/T2_reversingIOSApps.pdf)

# Анализ Вредоносных Программ

BlackHat 2015 (https://github.com/REhints/Publications/blob/master/Conferences/BH%272015/BH_2015.pdf)

Analysis of Disco Savings Adware (https://www.proteansec.com/whitepapers/Proteansec_Analysis_Disco_Savings.pdf)

You Dirty RAT: Analyzing an AlienSpy Payload (https://www.proofpoint.com/us/threat-insight/post/You-Dirty-RAT)

# Сеть

Reverse Engineering of Protocols from Network Traces (http://www.di.fc.ul.pt/~nuno/PAPERS/WCRE11.pdf)

# Обфускации и деобфускация

Advanced JS Deobfuscation Via AST and Partial Evaluation (http://blog.mindedsecurity.com/2015/10/advanced-js-deobfuscation-via-ast-and.html)

# Исследовательский инструментарий

IR Transformation Synthesis for Assembly Instructions (https://speakerdeck.com/snf/ir-transformation-synthesis-for-assembly-instructions)

# Распаковка

The Art of Unpacking (https://www.blackhat.com/presentations/bh-usa-07/Yason/Whitepaper/bh-usa-07-yason-WP.pdf)

# Windows

Defeating Windows Driver Signature Enforcement #1: default drivers (http://j00ru.vexillium.org/?p=1169)
Defeating Windows Driver Signature Enforcement #2: CSRSS and thread desktops (http://j00ru.vexillium.org/?p=1393)
Defeating Windows Driver Signature Enforcement #3: The Ultimate Encounter (http://j00ru.vexillium.org/?p=1455)

# Защита от патча

Bypassing PatchGuard on Windows x64 (http://www.uninformed.org/?v=3&a=3&t=txt)
Universal Patchguard and Driver Signature Enforcement Disable (https://github.com/hfiref0x/UPGDSED)

# Win32

PInvoke.net: PInvoke.net-это прежде всего wiki, позволяющая разработчикам находить, редактировать и добавлять сигнатуры PInvoke*, пользовательские типы и любую другую информацию, связанную с вызовом Win32 и других неуправляемых API из управляемого кода (написанного на таких языках, как C# или VB.NET). (http://www.pinvoke.net/)

# Дополнительные ссылки

Избранные ссылки по реверс-инжинирингу (https://zen.yandex.ru/media/id/5bbcbc1ba5bd5400a990e7d9/izbrannye-ssylki-po-reversinjiniringu-5d6fce26a06eaf00ad41e1fc)
Избранное: ссылки по reverse engineering (https://habr.com/ru/company/dsec/blog/334832/)
Библиотека Codeby (https://codeby.net/resources/categories/reverse-engineering.9/)
Telegram канал RAP ( Reverse | Assembler | PWN ) (https://t.me/ReverseAssemblerPWN) 

