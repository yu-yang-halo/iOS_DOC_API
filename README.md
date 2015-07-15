# iOS_DOC_API
本文档旨在记录apple官方文档的学习过程

I Xcode6.4文档
第一部分：Cocoa Touch Layer / UIKit / Guides / Cocoa Application Competencies（能力）

1.动画
  “动画其实是iOS与OS X呈现用户界面必须的一部分，也是用户体验该平台的必须的一部分“来自官方的这句话体现了动画的重要性，所以提示iOS开发人员要能很好的掌握它。
  CoreAnimation框架：两个平台主要的动画功能都是由它提供，它是由object-c提供的高速的，2D层的引擎接口。
The key technology of Core Animation is the layer. Layers are lightweight objects (CALayer) that, though similar to views, are actually model objects assigned to views. They encapsulate geometry, timing, and visual properties for a view that displays content based on those factors. All you must do is set the layer content, configure the animation properties, and then let Core Animation do its part.
2.Animations Must Have a Target, a Type, and Timing Details
3.Implicit Versus Explicit Animations

