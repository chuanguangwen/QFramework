![](DocRes/QFramework-icon-0.1.0-512x128.png)

[![](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/liangxiegame/QFramework/blob/master/LICENSE)
[![Documentation Status](./DocRes/passing.svg)](http://qframework.io)  [![Build Status](https://travis-ci.org/liangxiegame/QFramework.svg?branch=master)](https://travis-ci.org/liangxiegame/QFramework)
[![Coverage Status](https://coveralls.io/repos/github/liangxiegame/QFramework/badge.svg?branch=master)](https://coveralls.io/github/liangxiegame/QFramework?branch=master)

# QFramework 简介 Intro
  QFramework 是一套 **渐进式** 的 **快速开发** 框架。目标是作为无框架经验的公司、独立开发者、以及 Unity3D 初学者们的 **第一套框架**。框架内部积累了多个项目的在各个技术方向的解决方案。学习成本低，接入成本低，重构成本低，二次开发成本低，文档内容丰富(提供使用方式以及原理、开发文档)。
  
  QFramework is a **Progressive** and **RAD** framework.Goal is become indie developer and fresh man's **The First Framework**。It's include many project's tech solution.Easy 2 Learn,Easy 2 Install,Easy 2 Refactor,Easy 2 Modify,Feature Packed documents.
#### 技术支持 Tech Support：
* [文档 Document](http://qframework.io)
* **如在使用中遇到问题请提交 [这里 issue](https://github.com/liangxiegame/QFramework/issues/new)，我们团队会在一天内快速回复并着手解决。**
* **QQ群:623597263**
* **不想进群的同学也可以在 [这里 gitter](https://gitter.im/qframeworkio/qframework) 进行讨论**
#### 下载地址 Download:
* [Asset Store](http://u3d.as/SJ9)
* [各个独立模块下载 Modules](https://github.com/liangxiegame/QFramework/releases)
#### 赞助 Donate:
* 如果觉得不错可以在 [这里 Asset Store](http://u3d.as/SJ9) 给个 5 星哦~ give 5 star
* 或者给此仓库一个小小的 Star~ star this repository
* 以上这些都会转化成我们的动力,提供更好的技术服务! 
#### 运行环境
* Unity 5.5.x ~ 2017.x
#### 特性
* UI
* Action
* ResKit
#### 快速开始
Unity API GameObject 扩展:
``` csharp
gameObject
	// 1. gameObject.SetActive(true)
	.Show()
	// 2. gameObject.SetActive(false)
	.Hide()
	// 3. gameObject.name = "Yeah" (这是UnityEngine.Object的API)
	.Name("Yeah")
	// 4. gameObject.layer = 10
	.Layer(0)
	// 5. gameObject.layer = LayerMask.NameToLayer("Default);
	.Layer("Default")
	// 6. Destroy(gameObject) (这是UnityEngine.Object的API)
	.DestroySelf();
```
Unity API MonoBehaviour 扩展:
``` csharp
this
	// 1. this.gameObject.Show()
	.Show()
	// 2. this.gameObject.Hide()
	.Hide()
	// 3. this.gameObject.Name("Yeah")
	.Name("Yeah")
	// 4. gameObject.layer = 10
	.Layer(0)
	// 5. gameObject.layer = LayerMask.NameToLayer("Default);
	.Layer("Default")
	// 6. Destroy(this.gameObject)
	.DestroyGameObj();
```
#### 包含项目 Include Projects:
* [~~UniPM:A Package Manager For Unity3D~~](https://github.com/UniPM/UniPM)
* [LShortcut4Unity:A Short Cut Tools For Unity Editor](https://github.com/LoveOfCodeGod/LShortcut4Unity)
* [UniRx](https://github.com/neuecc/UniRx)
* [Json.net](https://github.com/JamesNK/Newtonsoft.Json)
* [Catlib.Core](https://github.com/CatLib/Core)
* [UnityEditorMemo](https://github.com/charcolle/UnityEditorMemo)
#### 参考 Reference:
* [HGFramework: Unity3D客户端框架](https://github.com/zhutaorun/HGFramework)
* [Qarth: Framework For Game Develop With Unity3d](https://github.com/SnowCold/Qarth)
* [GameFramework:A game framework based on Unity 5.3 and later versions](https://github.com/EllanJiang/GameFramework)
* [cocos2d/cocos2d-x](https://github.com/cocos2d/cocos2d-x)
* [ResetCore.Unity](https://github.com/vgvgvvv/ResetCore.Unity)
#### 贡献者/感谢 Developer/Contributor:
- [@karsion](https://github.com/karsion)
- [@huibinye](https://github.com/HUIBINYE)
- [@dtknowlove](https://github.com/dtknowlove)
- [@vin129](https://github.com/vin129)
- [@kevin](https://github.com/KEVIN-ZED)
- [@SilenceT](https://github.com/SilenceT)
- [@imagicbell](https://github.com/imagicbell)
- [@liangxie](https://github.com/liangxieq)
#### 教程 Tutorial
* [如何打造自己的框架](http://liangxiegame.com/post/1/)
* [零基础开始打造自己的框架](http://liangxiegame.com/post/26/)
* [C#入门与框架设计(视频)](http://edu.manew.com/course/431)
