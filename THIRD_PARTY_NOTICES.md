# Third-party notices / 第三方素材声明

核实日期：2026-10-08。本文随源码、公开展示仓库及独立 index.html 一起分发。

## 授权范围

根目录 LICENSE 的 MIT 授权（Copyright (c) 2026 OliverYGM）适用于 OliverYGM 有权授权的项目代码及随附原创文档；项目自行绘制的 SVG 和 CSS 图形作为项目代码按 MIT 分发。第三方题库条目、录音等仍适用其各自许可，不能用项目 MIT 声明替换原作者署名、同方式共享或其他条件。源码中的项目原创练习文本随代码按 MIT 提供；该授权仅及于项目有权授权的部分。

MIT 允许复制、修改、分发和商业使用，须保留版权及许可声明，并不提供保证。本次许可整理不证明ICP备案、其他网站合规或所有素材的底层权利均已完成审查。

## 题库

assets/question-bank.json 的 sources 保留原来源与 MIT 全文，以下声明从该文件逐项复制，不改写原作者归属。核对了六个上游的许可标识或许可证文件。BIP39 英文词表与 trezor/python-mnemonic 的词表一致；后者 LICENSE 中的 Pavol Rusnak 声明与本题库一致，BIP39 规范本身也标记 License: MIT。

BIP39 依据：https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki
对应实现许可：https://github.com/trezor/python-mnemonic/blob/master/LICENSE
对应词表：https://github.com/trezor/python-mnemonic/blob/master/src/mnemonic/wordlist/english.txt
BIP39 规范列出的作者：Marek Palatinus、Pavol Rusnak、Aaron Voisine、Sean Bowe。

使用包括词表筛选、英中标签匹配、词频筛选、拼音转换、成语及歇后语题面选择、古诗分句。原创英文短语和生活场景短文来自项目编写的句型。未采用现代诗歌、译本注释或词典的长篇解释作为练习段落。

上游仓库的 MIT 许可证是本次使用的授权依据，但不等于对其全部原始数据来源作出独立权利保证。尤其词典译义、汇编及现代编辑内容仍可能存在上游未披露的权利；后续收到权利人反馈时应核实并移除或替换相应条目。

### BIP39 English word list

来源：https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt

```text
The MIT License (MIT)

Copyright (c) 2013-2016 Pavol Rusnak

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### ECDICT bilingual labels

来源：https://github.com/skywind3000/ECDICT

```text
MIT License

Copyright (c) 2025 Linwei

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### jieba vocabulary frequencies

来源：https://github.com/fxsjy/jieba

```text
The MIT License (MIT)

Copyright (c) 2013 Sun Junyi

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

### python-pinyin pronunciation data

来源：https://github.com/mozillazg/python-pinyin

```text
The MIT License (MIT)

Copyright (c) 2016 mozillazg, 闲耘 <hotoo.cn@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

### chinese-xinhua idiom and riddle heads

来源：https://github.com/pwxcoo/chinese-xinhua

```text
MIT License

Copyright (c) 2018 PWXCOO

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### chinese-poetry classical verses

来源：https://github.com/chinese-poetry/chinese-poetry

```text
The MIT License (MIT)

Copyright (c) 2016 JackeyGao

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

## 图形与字体

assets/logo.svg，以及 src/page.html、src/ui.js 和 src/style.css 中的键盘、猫、植物、虫怪、气球、天气、图标和动画，均为本项目绘制的 SVG/CSS 代码，按项目 MIT 许可分发；未引入第三方图标包、角色贴图或字体文件。植物守卫的玩法不构成对任何现有游戏角色、美术、音乐或商标的授权。

previews/ 下的 PNG 为本项目页面的历史截图，可能显示当时设备的系统字体或 emoji 渲染。截图不扩展这些第三方字体或字形的许可，也不包含可播放的语音数据。

题库里的 emoji 为 Unicode 文本标记，当前主要插图由项目 SVG 绘制。浏览器可能使用设备自带字体显示文本或少量符号；这些系统字体及其字形不属于本项目的 MIT 授权范围，项目不捆绑或分发字体文件。

## 背景音乐与效果音

src/ui.js 使用 Web Audio 生成背景旋律、按键、击中、失误和奖励提示。对应合成代码及项目编写的旋律按 MIT 分发；没有嵌入外部音乐录音。

## 鼓励语音

三段录音均由 Dvortygirl 录制，原文件来自 Wikimedia Commons；文件页给出的许可用于音频本身，不能把网站页脚关于元数据或网页文字的许可误当作音频许可。以下三段为真人单词录音，不是 Apple 系统声音，也不表示录音者认可或代言本项目。

作者页面：https://commons.wikimedia.org/wiki/User:Dvortygirl

| 当前文件 | 原作品 | 音频许可 |
| --- | --- | --- |
| assets/good.wav | En-us-good.ogg，Dvortygirl，原说明为 2005 年录制、2011 年替换上传 | 作者释放至公有领域；如当地法律不允许，则给予任何用途、不附条件的使用授权（法律要求除外） |
| assets/great.wav | En-us-great.ogg，Dvortygirl，2005 年 | 作者释放至公有领域，并提供同样的任何用途、无条件后备授权 |
| assets/excellent.wav | En-us-excellent.ogg，Dvortygirl，2006 年 | 本项目选择 CC BY-SA 3.0 Unported；原文件同时提供其他许可，不在本项目中据此另行改标 |
| assets/表扬语音试听.wav | 按顺序汇集以上三段并加入间隔 | 保留全部署名；含 Excellent 的处理版本，试听合集按 CC BY-SA 3.0 提供 |

许可链接：https://creativecommons.org/licenses/by-sa/3.0/

原文件及固定版本说明：
- Good：https://commons.wikimedia.org/wiki/File:En-us-good.ogg （https://commons.wikimedia.org/w/index.php?title=File:En-us-good.ogg&oldid=963828927）
- Great：https://commons.wikimedia.org/wiki/File:En-us-great.ogg （https://commons.wikimedia.org/w/index.php?title=File:En-us-great.ogg&oldid=1229135663）
- Excellent：https://commons.wikimedia.org/wiki/File:En-us-excellent.ogg （https://commons.wikimedia.org/w/index.php?title=File:En-us-excellent.ogg&oldid=1229130933）

修改说明：原 Ogg 录音解码为单声道 24 kHz、16-bit PCM WAV，去直流偏置，使用 7 kHz 的轻柔低通，目标 RMS -22 dBFS、峰值上限 -6 dBFS，加入 12 ms 边缘淡入淡出及两端各 60 ms 静音；没有替换发音、音色或单词。试听合集在词间加入 450 ms 间隔。来源 SHA-1、当前文件 SHA-256 和处理参数记录于 assets/audio-sources.json。

CC BY-SA 3.0 允许复制、公开播放、修改和商业使用；使用 Excellent 及其处理版本时须保留 Dvortygirl 署名、作品来源、许可链接和修改说明，音频改编须以相同或兼容许可分发。含该录音的同步视听改编也须按许可的改编条款判断，不能笼统将含第三方录音的全部衍生成品标为 MIT。与该录音独立的软件代码继续适用项目 MIT。下文附许可全文，独立网页同时内嵌这些声明。

## 已替换的 Apple 系统声音及历史残留

原 Good / Great / Excellent 及合并试听文件曾由 macOS Samantha 系统声音生成。Apple macOS Tahoe 26 许可第 2F 条只允许所述个人、非商业用途，并明确限制盈利、非营利、公开分享及商业场景中的系统声音使用、录制、发布和再分发。本项目没有取得例外授权，不能将原音频改标为 MIT。

条款依据：https://www.apple.com/legal/sla/docs/macOSTahoe.pdf （英文第 2F 条，PDF 第 3 页）。当前音频文件和新生成 index.html 已全部替换，构建时按已核实的音频 SHA-256 校验，防止原音频或未记录素材被意外内嵌。

2026-10-08 的只读核验确认：Cloudflare 旧预览部署前缀 `a3e058fb` 和 `33abb881` 仍可访问，三段内嵌录音的 SHA-256 均匹配 `assets/audio-sources.json` 记录的已停用音频摘要。这两份预览不会因主网址更新而自动替换；应优先在后续获授权的清理中处理。

这次修改不重写 Git 历史，也不删除旧部署。此前提交、旧 Cloudflare 预览部署、GitHub Actions 历史制品、早前下载的网页/压缩包和浏览器缓存仍可能保留原音频。建议后续经项目所有者授权后清理可访问的旧预览部署与历史制品，更新已分发的下载包和缓存；如果需要处理 Git 历史，另行制定迁移或重写方案，或者向 Apple 核实例外授权。本次新版本的许可声明不追溯授权这些旧音频。

## CC BY-SA 3.0 Unported 许可全文

来源：https://creativecommons.org/licenses/by-sa/3.0/legalcode.txt

```text
Creative Commons Legal Code

Attribution-ShareAlike 3.0 Unported

    CREATIVE COMMONS CORPORATION IS NOT A LAW FIRM AND DOES NOT PROVIDE
    LEGAL SERVICES. DISTRIBUTION OF THIS LICENSE DOES NOT CREATE AN
    ATTORNEY-CLIENT RELATIONSHIP. CREATIVE COMMONS PROVIDES THIS
    INFORMATION ON AN "AS-IS" BASIS. CREATIVE COMMONS MAKES NO WARRANTIES
    REGARDING THE INFORMATION PROVIDED, AND DISCLAIMS LIABILITY FOR
    DAMAGES RESULTING FROM ITS USE.

License

THE WORK (AS DEFINED BELOW) IS PROVIDED UNDER THE TERMS OF THIS CREATIVE
COMMONS PUBLIC LICENSE ("CCPL" OR "LICENSE"). THE WORK IS PROTECTED BY
COPYRIGHT AND/OR OTHER APPLICABLE LAW. ANY USE OF THE WORK OTHER THAN AS
AUTHORIZED UNDER THIS LICENSE OR COPYRIGHT LAW IS PROHIBITED.

BY EXERCISING ANY RIGHTS TO THE WORK PROVIDED HERE, YOU ACCEPT AND AGREE
TO BE BOUND BY THE TERMS OF THIS LICENSE. TO THE EXTENT THIS LICENSE MAY
BE CONSIDERED TO BE A CONTRACT, THE LICENSOR GRANTS YOU THE RIGHTS
CONTAINED HERE IN CONSIDERATION OF YOUR ACCEPTANCE OF SUCH TERMS AND
CONDITIONS.

1. Definitions

 a. "Adaptation" means a work based upon the Work, or upon the Work and
    other pre-existing works, such as a translation, adaptation,
    derivative work, arrangement of music or other alterations of a
    literary or artistic work, or phonogram or performance and includes
    cinematographic adaptations or any other form in which the Work may be
    recast, transformed, or adapted including in any form recognizably
    derived from the original, except that a work that constitutes a
    Collection will not be considered an Adaptation for the purpose of
    this License. For the avoidance of doubt, where the Work is a musical
    work, performance or phonogram, the synchronization of the Work in
    timed-relation with a moving image ("synching") will be considered an
    Adaptation for the purpose of this License.
 b. "Collection" means a collection of literary or artistic works, such as
    encyclopedias and anthologies, or performances, phonograms or
    broadcasts, or other works or subject matter other than works listed
    in Section 1(f) below, which, by reason of the selection and
    arrangement of their contents, constitute intellectual creations, in
    which the Work is included in its entirety in unmodified form along
    with one or more other contributions, each constituting separate and
    independent works in themselves, which together are assembled into a
    collective whole. A work that constitutes a Collection will not be
    considered an Adaptation (as defined below) for the purposes of this
    License.
 c. "Creative Commons Compatible License" means a license that is listed
    at https://creativecommons.org/compatiblelicenses that has been
    approved by Creative Commons as being essentially equivalent to this
    License, including, at a minimum, because that license: (i) contains
    terms that have the same purpose, meaning and effect as the License
    Elements of this License; and, (ii) explicitly permits the relicensing
    of adaptations of works made available under that license under this
    License or a Creative Commons jurisdiction license with the same
    License Elements as this License.
 d. "Distribute" means to make available to the public the original and
    copies of the Work or Adaptation, as appropriate, through sale or
    other transfer of ownership.
 e. "License Elements" means the following high-level license attributes
    as selected by Licensor and indicated in the title of this License:
    Attribution, ShareAlike.
 f. "Licensor" means the individual, individuals, entity or entities that
    offer(s) the Work under the terms of this License.
 g. "Original Author" means, in the case of a literary or artistic work,
    the individual, individuals, entity or entities who created the Work
    or if no individual or entity can be identified, the publisher; and in
    addition (i) in the case of a performance the actors, singers,
    musicians, dancers, and other persons who act, sing, deliver, declaim,
    play in, interpret or otherwise perform literary or artistic works or
    expressions of folklore; (ii) in the case of a phonogram the producer
    being the person or legal entity who first fixes the sounds of a
    performance or other sounds; and, (iii) in the case of broadcasts, the
    organization that transmits the broadcast.
 h. "Work" means the literary and/or artistic work offered under the terms
    of this License including without limitation any production in the
    literary, scientific and artistic domain, whatever may be the mode or
    form of its expression including digital form, such as a book,
    pamphlet and other writing; a lecture, address, sermon or other work
    of the same nature; a dramatic or dramatico-musical work; a
    choreographic work or entertainment in dumb show; a musical
    composition with or without words; a cinematographic work to which are
    assimilated works expressed by a process analogous to cinematography;
    a work of drawing, painting, architecture, sculpture, engraving or
    lithography; a photographic work to which are assimilated works
    expressed by a process analogous to photography; a work of applied
    art; an illustration, map, plan, sketch or three-dimensional work
    relative to geography, topography, architecture or science; a
    performance; a broadcast; a phonogram; a compilation of data to the
    extent it is protected as a copyrightable work; or a work performed by
    a variety or circus performer to the extent it is not otherwise
    considered a literary or artistic work.
 i. "You" means an individual or entity exercising rights under this
    License who has not previously violated the terms of this License with
    respect to the Work, or who has received express permission from the
    Licensor to exercise rights under this License despite a previous
    violation.
 j. "Publicly Perform" means to perform public recitations of the Work and
    to communicate to the public those public recitations, by any means or
    process, including by wire or wireless means or public digital
    performances; to make available to the public Works in such a way that
    members of the public may access these Works from a place and at a
    place individually chosen by them; to perform the Work to the public
    by any means or process and the communication to the public of the
    performances of the Work, including by public digital performance; to
    broadcast and rebroadcast the Work by any means including signs,
    sounds or images.
 k. "Reproduce" means to make copies of the Work by any means including
    without limitation by sound or visual recordings and the right of
    fixation and reproducing fixations of the Work, including storage of a
    protected performance or phonogram in digital form or other electronic
    medium.

2. Fair Dealing Rights. Nothing in this License is intended to reduce,
limit, or restrict any uses free from copyright or rights arising from
limitations or exceptions that are provided for in connection with the
copyright protection under copyright law or other applicable laws.

3. License Grant. Subject to the terms and conditions of this License,
Licensor hereby grants You a worldwide, royalty-free, non-exclusive,
perpetual (for the duration of the applicable copyright) license to
exercise the rights in the Work as stated below:

 a. to Reproduce the Work, to incorporate the Work into one or more
    Collections, and to Reproduce the Work as incorporated in the
    Collections;
 b. to create and Reproduce Adaptations provided that any such Adaptation,
    including any translation in any medium, takes reasonable steps to
    clearly label, demarcate or otherwise identify that changes were made
    to the original Work. For example, a translation could be marked "The
    original work was translated from English to Spanish," or a
    modification could indicate "The original work has been modified.";
 c. to Distribute and Publicly Perform the Work including as incorporated
    in Collections; and,
 d. to Distribute and Publicly Perform Adaptations.
 e. For the avoidance of doubt:

     i. Non-waivable Compulsory License Schemes. In those jurisdictions in
        which the right to collect royalties through any statutory or
        compulsory licensing scheme cannot be waived, the Licensor
        reserves the exclusive right to collect such royalties for any
        exercise by You of the rights granted under this License;
    ii. Waivable Compulsory License Schemes. In those jurisdictions in
        which the right to collect royalties through any statutory or
        compulsory licensing scheme can be waived, the Licensor waives the
        exclusive right to collect such royalties for any exercise by You
        of the rights granted under this License; and,
   iii. Voluntary License Schemes. The Licensor waives the right to
        collect royalties, whether individually or, in the event that the
        Licensor is a member of a collecting society that administers
        voluntary licensing schemes, via that society, from any exercise
        by You of the rights granted under this License.

The above rights may be exercised in all media and formats whether now
known or hereafter devised. The above rights include the right to make
such modifications as are technically necessary to exercise the rights in
other media and formats. Subject to Section 8(f), all rights not expressly
granted by Licensor are hereby reserved.

4. Restrictions. The license granted in Section 3 above is expressly made
subject to and limited by the following restrictions:

 a. You may Distribute or Publicly Perform the Work only under the terms
    of this License. You must include a copy of, or the Uniform Resource
    Identifier (URI) for, this License with every copy of the Work You
    Distribute or Publicly Perform. You may not offer or impose any terms
    on the Work that restrict the terms of this License or the ability of
    the recipient of the Work to exercise the rights granted to that
    recipient under the terms of the License. You may not sublicense the
    Work. You must keep intact all notices that refer to this License and
    to the disclaimer of warranties with every copy of the Work You
    Distribute or Publicly Perform. When You Distribute or Publicly
    Perform the Work, You may not impose any effective technological
    measures on the Work that restrict the ability of a recipient of the
    Work from You to exercise the rights granted to that recipient under
    the terms of the License. This Section 4(a) applies to the Work as
    incorporated in a Collection, but this does not require the Collection
    apart from the Work itself to be made subject to the terms of this
    License. If You create a Collection, upon notice from any Licensor You
    must, to the extent practicable, remove from the Collection any credit
    as required by Section 4(c), as requested. If You create an
    Adaptation, upon notice from any Licensor You must, to the extent
    practicable, remove from the Adaptation any credit as required by
    Section 4(c), as requested.
 b. You may Distribute or Publicly Perform an Adaptation only under the
    terms of: (i) this License; (ii) a later version of this License with
    the same License Elements as this License; (iii) a Creative Commons
    jurisdiction license (either this or a later license version) that
    contains the same License Elements as this License (e.g.,
    Attribution-ShareAlike 3.0 US)); (iv) a Creative Commons Compatible
    License. If you license the Adaptation under one of the licenses
    mentioned in (iv), you must comply with the terms of that license. If
    you license the Adaptation under the terms of any of the licenses
    mentioned in (i), (ii) or (iii) (the "Applicable License"), you must
    comply with the terms of the Applicable License generally and the
    following provisions: (I) You must include a copy of, or the URI for,
    the Applicable License with every copy of each Adaptation You
    Distribute or Publicly Perform; (II) You may not offer or impose any
    terms on the Adaptation that restrict the terms of the Applicable
    License or the ability of the recipient of the Adaptation to exercise
    the rights granted to that recipient under the terms of the Applicable
    License; (III) You must keep intact all notices that refer to the
    Applicable License and to the disclaimer of warranties with every copy
    of the Work as included in the Adaptation You Distribute or Publicly
    Perform; (IV) when You Distribute or Publicly Perform the Adaptation,
    You may not impose any effective technological measures on the
    Adaptation that restrict the ability of a recipient of the Adaptation
    from You to exercise the rights granted to that recipient under the
    terms of the Applicable License. This Section 4(b) applies to the
    Adaptation as incorporated in a Collection, but this does not require
    the Collection apart from the Adaptation itself to be made subject to
    the terms of the Applicable License.
 c. If You Distribute, or Publicly Perform the Work or any Adaptations or
    Collections, You must, unless a request has been made pursuant to
    Section 4(a), keep intact all copyright notices for the Work and
    provide, reasonable to the medium or means You are utilizing: (i) the
    name of the Original Author (or pseudonym, if applicable) if supplied,
    and/or if the Original Author and/or Licensor designate another party
    or parties (e.g., a sponsor institute, publishing entity, journal) for
    attribution ("Attribution Parties") in Licensor's copyright notice,
    terms of service or by other reasonable means, the name of such party
    or parties; (ii) the title of the Work if supplied; (iii) to the
    extent reasonably practicable, the URI, if any, that Licensor
    specifies to be associated with the Work, unless such URI does not
    refer to the copyright notice or licensing information for the Work;
    and (iv) , consistent with Ssection 3(b), in the case of an
    Adaptation, a credit identifying the use of the Work in the Adaptation
    (e.g., "French translation of the Work by Original Author," or
    "Screenplay based on original Work by Original Author"). The credit
    required by this Section 4(c) may be implemented in any reasonable
    manner; provided, however, that in the case of a Adaptation or
    Collection, at a minimum such credit will appear, if a credit for all
    contributing authors of the Adaptation or Collection appears, then as
    part of these credits and in a manner at least as prominent as the
    credits for the other contributing authors. For the avoidance of
    doubt, You may only use the credit required by this Section for the
    purpose of attribution in the manner set out above and, by exercising
    Your rights under this License, You may not implicitly or explicitly
    assert or imply any connection with, sponsorship or endorsement by the
    Original Author, Licensor and/or Attribution Parties, as appropriate,
    of You or Your use of the Work, without the separate, express prior
    written permission of the Original Author, Licensor and/or Attribution
    Parties.
 d. Except as otherwise agreed in writing by the Licensor or as may be
    otherwise permitted by applicable law, if You Reproduce, Distribute or
    Publicly Perform the Work either by itself or as part of any
    Adaptations or Collections, You must not distort, mutilate, modify or
    take other derogatory action in relation to the Work which would be
    prejudicial to the Original Author's honor or reputation. Licensor
    agrees that in those jurisdictions (e.g. Japan), in which any exercise
    of the right granted in Section 3(b) of this License (the right to
    make Adaptations) would be deemed to be a distortion, mutilation,
    modification or other derogatory action prejudicial to the Original
    Author's honor and reputation, the Licensor will waive or not assert,
    as appropriate, this Section, to the fullest extent permitted by the
    applicable national law, to enable You to reasonably exercise Your
    right under Section 3(b) of this License (right to make Adaptations)
    but not otherwise.

5. Representations, Warranties and Disclaimer

UNLESS OTHERWISE MUTUALLY AGREED TO BY THE PARTIES IN WRITING, LICENSOR
OFFERS THE WORK AS-IS AND MAKES NO REPRESENTATIONS OR WARRANTIES OF ANY
KIND CONCERNING THE WORK, EXPRESS, IMPLIED, STATUTORY OR OTHERWISE,
INCLUDING, WITHOUT LIMITATION, WARRANTIES OF TITLE, MERCHANTIBILITY,
FITNESS FOR A PARTICULAR PURPOSE, NONINFRINGEMENT, OR THE ABSENCE OF
LATENT OR OTHER DEFECTS, ACCURACY, OR THE PRESENCE OF ABSENCE OF ERRORS,
WHETHER OR NOT DISCOVERABLE. SOME JURISDICTIONS DO NOT ALLOW THE EXCLUSION
OF IMPLIED WARRANTIES, SO SUCH EXCLUSION MAY NOT APPLY TO YOU.

6. Limitation on Liability. EXCEPT TO THE EXTENT REQUIRED BY APPLICABLE
LAW, IN NO EVENT WILL LICENSOR BE LIABLE TO YOU ON ANY LEGAL THEORY FOR
ANY SPECIAL, INCIDENTAL, CONSEQUENTIAL, PUNITIVE OR EXEMPLARY DAMAGES
ARISING OUT OF THIS LICENSE OR THE USE OF THE WORK, EVEN IF LICENSOR HAS
BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.

7. Termination

 a. This License and the rights granted hereunder will terminate
    automatically upon any breach by You of the terms of this License.
    Individuals or entities who have received Adaptations or Collections
    from You under this License, however, will not have their licenses
    terminated provided such individuals or entities remain in full
    compliance with those licenses. Sections 1, 2, 5, 6, 7, and 8 will
    survive any termination of this License.
 b. Subject to the above terms and conditions, the license granted here is
    perpetual (for the duration of the applicable copyright in the Work).
    Notwithstanding the above, Licensor reserves the right to release the
    Work under different license terms or to stop distributing the Work at
    any time; provided, however that any such election will not serve to
    withdraw this License (or any other license that has been, or is
    required to be, granted under the terms of this License), and this
    License will continue in full force and effect unless terminated as
    stated above.

8. Miscellaneous

 a. Each time You Distribute or Publicly Perform the Work or a Collection,
    the Licensor offers to the recipient a license to the Work on the same
    terms and conditions as the license granted to You under this License.
 b. Each time You Distribute or Publicly Perform an Adaptation, Licensor
    offers to the recipient a license to the original Work on the same
    terms and conditions as the license granted to You under this License.
 c. If any provision of this License is invalid or unenforceable under
    applicable law, it shall not affect the validity or enforceability of
    the remainder of the terms of this License, and without further action
    by the parties to this agreement, such provision shall be reformed to
    the minimum extent necessary to make such provision valid and
    enforceable.
 d. No term or provision of this License shall be deemed waived and no
    breach consented to unless such waiver or consent shall be in writing
    and signed by the party to be charged with such waiver or consent.
 e. This License constitutes the entire agreement between the parties with
    respect to the Work licensed here. There are no understandings,
    agreements or representations with respect to the Work not specified
    here. Licensor shall not be bound by any additional provisions that
    may appear in any communication from You. This License may not be
    modified without the mutual written agreement of the Licensor and You.
 f. The rights granted under, and the subject matter referenced, in this
    License were drafted utilizing the terminology of the Berne Convention
    for the Protection of Literary and Artistic Works (as amended on
    September 28, 1979), the Rome Convention of 1961, the WIPO Copyright
    Treaty of 1996, the WIPO Performances and Phonograms Treaty of 1996
    and the Universal Copyright Convention (as revised on July 24, 1971).
    These rights and subject matter take effect in the relevant
    jurisdiction in which the License terms are sought to be enforced
    according to the corresponding provisions of the implementation of
    those treaty provisions in the applicable national law. If the
    standard suite of rights granted under applicable copyright law
    includes additional rights not granted under this License, such
    additional rights are deemed to be included in the License; this
    License is not intended to restrict the license of any rights under
    applicable law.


Creative Commons Notice

    Creative Commons is not a party to this License, and makes no warranty
    whatsoever in connection with the Work. Creative Commons will not be
    liable to You or any party on any legal theory for any damages
    whatsoever, including without limitation any general, special,
    incidental or consequential damages arising in connection to this
    license. Notwithstanding the foregoing two (2) sentences, if Creative
    Commons has expressly identified itself as the Licensor hereunder, it
    shall have all rights and obligations of Licensor.

    Except for the limited purpose of indicating to the public that the
    Work is licensed under the CCPL, Creative Commons does not authorize
    the use by either party of the trademark "Creative Commons" or any
    related trademark or logo of Creative Commons without the prior
    written consent of Creative Commons. Any permitted use will be in
    compliance with Creative Commons' then-current trademark usage
    guidelines, as may be published on its website or otherwise made
    available upon request from time to time. For the avoidance of doubt,
    this trademark restriction does not form part of the License.

    Creative Commons may be contacted at https://creativecommons.org/.
```
