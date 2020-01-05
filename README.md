# RFC
RFC（Request For Comments）意即“请求评论”，包含了关于Internet的几乎所有重要的文字资料。

> Request For Comments（RFC），是一系列以编号排定的文件。文件收集了有关互联网相关信息，以及UNIX和互联网社区的软件文件。RFC文件是由Internet Society（ISOC）赞助发行。基本的互联网通信协议都有在RFC文件内详细说明。RFC文件还额外加入许多在标准内的论题，例如对于互联网新开发的协议及发展中所有的记录。因此几乎所有的互联网标准都有收录在RFC文件之中。


# 编辑机制
RFC（Request For Comments）意即“请求评论”，包含了关于Internet的几乎所有重要的文字资料。如果你想成为网络方面的专家，那么RFC无疑是最重要也是最经常需要用到的资料之一，所以RFC享有网络知识圣经之美誉。通常，当某家机构或团体开发出了一套标准或提出对某种标准的设想，想要征询外界的意见时，就会在Internet上发放一份RFC，对这一问题感兴趣的人可以阅读该RFC并提出自己的意见；绝大部分网络标准的制定都是以RFC的形式开始，经过大量的论证和修改过程，由主要的标准化组织所指定的，但在RFC中所收录的文件并不都是正在使用或为大家所公认的，也有很大一部分只在某个局部领域被使用或并没有被采用，一份RFC具体处于什么状态都在文件中作了明确的标识。

RFC由一系列草案组成，起始于1969年（第一个RFC文档发布于1969年4月7日，参见“RFC30年”，RFC2555”），RFC文档是一系列关于Internet（早期为ARPANET）的技术资料汇编。这些文档详细讨论了计算机网络的方方面面，重点在网络协议，进程，程序，概念以及一些会议纪要，意见，各种观点等。

“RFC编辑者”是RFC文档的出版者，它负责RFC最终文档的编辑审订。“RFC编辑者”也保留有RFC的主文件，称为RFC索引，用户可以在线检索。在RFC近30年的历史中，“RFC编辑者”一直由约翰·普斯特尔（Jon Postel）来担任，而“RFC编辑者”则由一个工作小组来担任，这个小组受到“互联网协会”（Internet Society）的支持和帮助。

RFC编辑者负责RFC以及RFC的整体结构文档，并维护RFC的索引。Internet协议族的文档部分（由Internet工程委员会“因特网工程师任务组”IETF以及IETF 下属的“因特网工程师指导组”IESG 定义），也做为RFC文档出版。因此，RFC在Internet相关标准中有着重要的地位。

RFC编辑者的职责是由Internet 中的大家提议形成的，所出版的语言也就和Internet一样。IETF和ISOC是代表了世界各地的国际性组织，英语是IETF的第一工作语言，也是IETF的正式出版语言。RFC 2026 "The Internet Standards Process -- Revision 3" 允许RFC翻译成其他不同的语言。但是不能保证其翻译版本是完全正确的。因此，RFC编辑不对非英语的版本负责，而只是指明了哪里有非英语的版本，将这些信息列在WEB页上。


# 处理过程编辑
一个RFC文件在成为官方标准前一般至少要经历4个阶段（RFC2026）：因特网草案、建议标准、草案标准、因特网标准。

第一步RFC的出版是作为一个Internet 草案发布，可以阅读并对其进行注释。准备一个RFC草案，我们要求作者先阅读IETF的一个文档"Considerations for Internet Drafts". 它包括了许多关于RFC以及Internet草案格式的有用信息。作者还应阅读另外一个相关的文档RFC 2223 "Instructions to Authors"。


# 分类编辑
RFC文档大致可以分为以下几类。

## STD RFC
按照RFC1311的定义，STD RFC是指那些已经或者致力于成为Internet标准的RFC。只有经过完全Internet标准化过程的RFC才可以有STD编号，STD编号是不变的，而其涉及到的 RFC文档可能不只一个，其RFC编号也会更新。如STD13（Domain Name System）就涉及RFC1034和RFC1035。STD的标准化过程要经过几个步骤，首先由IETF起草标准（也可能是其他组织和个人，但一般都是和IETF共同完成的），形成Internet Draft（ID），ID没有RFC编号。如果ID在6个月内IESG没有建议成为RFC，则取消此ID。成为RFC后，还要经过一系列的审查、修订、测试等才能最终成为Internet标准。

## BCP RFC
由于Internet应用领域广泛，各种不同的组织有不同的使用目的和使用规则，IETF除了建议STD以外，也有必要对于Internet的使用和管理提供一些一般性的指导，同时也为IETF、IAB、IESG提供一种渠道，以便推动某一方面的工作，反映其技术趋向，反映这些组织本身的工作进展。于是，1995年以RFC1818定义了BCP，即Best Current Practice。BCP同时有一个BCP编号和一个RFC编号，一旦约定了一个BCP编号，就不会再变，而其RFC编号则可能会经过修订不断更新。例如反映Internet标准化工作程序的BCP9的RFC编号就从RFC1602上升到RFC2026，相应地就废弃了RFC1602。BCP在发表以前，以电子邮件的形式广泛征求IETF的意见，经过IESG的审查，通过后即正式发表。但是BCP本身不是Internet标准。

## FYI RFC
FYI是For Your Information的简写，1990年发表的RFC1150（FYI1）定义了FYI，FYI也同时有一个FYI编号和一个RFC编号，FYI编号是固定的。FYI主要是提供有关Internet的知识性内容。所有的FYI在提交到RFC编辑以前，必须先经过IETF的User Services WorkingGro up审查。

## 其他RFC
除了STD、BCP、FYI以外还有其他一些RFC。从RFC899开始，所有以99结尾的RFC都是对此前99个RFC的一个概括。如RFC1999就是对RFC1900到RFC1999的一个简单概括。除了上述分类以外，还有一些描述RFC的方法。与Internet标准化过程（Internet Standards Process）有关的规范可以分为两类，即 Technical Specification（TS），Applicability Statement（AS）。

TS是对协议、规则、格式、实用程序的描述。AS是描述在何种环境，以及怎样在Internet中使用TS；AS所涉及的并不一定全是Internet标准，比如IEEE、ITU、ISO组织的一些标准，大家所熟悉的ASCII标准就是一例。AS应该对其涉及的TS规定相应的级别"Requirement Level"，这些"Require ment Level"如下：Required（Req），相当于必须实现，如IP、ICMP；Recommended（Rec），鼓励使用，如TELNET；Elective（Elc），可选择的； Limited Use，只限于特定的用户，一般说来用于对一些新的协议做试验； ·Not Recommended，不要使用，很可能是过时的。"Maturity Level"也是用来描述TS和AS的一种方式，它反映这些标准是否成熟。对于致力于成为STD的TS和AS有三种"Maturity Level"。Proposed Standard，基本成熟，但还需要进一步的试验证实其可行性。除非是用来验证该协议的可行性，不要将其视为标准实现。Draft Standard，需要两个独立的，而且具有相互操作性的实例验证该协议的每一个方面。可以将其视为最终的标准草案；Internet Standard，最终的Internet标准，同时赋予一个STD编号。除此之外的TS和AS分为以下几种"Maturity Level"。Experimental，一般是反映一些研究和开发的成果，只应将此看作是一般性的信息。Informational，反映与Internet标准有关的一般性信息。有些也是有关非Intern et组织开发的一些协议，但必须得到协议开发者的许可。Historic，是一些被新的标准取代或者是已经过时废弃不用的标准。STD1（RFC2200）——Internet Official Protocol Standards，定期更新，反映最新的 Internet标准。另外，对于关注Internet的人来说，应该经常注意查阅BCP9的最新内容。

# 注意事项编辑
1、一是需要确定它是最新的文档，二是需要注意RFC文档的类别；
2、所有的RFC文档都要经历评论和反馈过程，并且在这一段时间内它们会被划分为不同的类别；
3、RFC文档一旦被提交，IETF和IAB组织将审查RFC文档，通过后可以成为一项标准；
4、RFC文档按照它发展与成熟的过程可以分为标准、草案标准、提案标准、实验性的、信息性或历史性的；
5、RFC文档又可以分为被要求、被推荐、被选择、受限制使用或不被推荐。

