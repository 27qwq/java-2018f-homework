#抽象类
#####Main
作为一个创世界的函数，声明了一个二维空间，由这个二维空间来展现葫芦娃和蝎子精之间的对抗。
#####生物体
1.生物体中设置了名字，坐标等属性，以及设置坐标的方法。
2.利用继承的思想，将葫芦娃、蝎子精等作为生物体的子类，这样这些生物体都可以使用设置坐标setXY的方法了。
#####空间
1.在空间中将了所有的生物体类实体化。
2.用setPace()方法，将设置各类生物体在空间中的位置。
3.用printSapce()方法，将空间的整个样貌打印出来。
#####阵型
阵型这个类中，将每个阵型写成了方法，阵型的实现用到了生物体的setXY方法。其中长蛇阵牵扯到了函数的重载。

#反思
1.对面向对象的思想了解了一些，但还是很难适应这样的思维。
2.要将整个世界抽象成一个一个类，所以我觉得这个世界有的就是一个二维空间，各种各样的生物体，以及各种各样的阵型。
3.对于生物体，没有想到要将他们集合成正义的一方或邪恶的一方，我看了别的同学的代码，很多人都有这么做，在下次修改中应该加入这个思想。
4.对于阵型来说，我将阵型设置成了一个一个的方法，可能把阵型写成一个一个的类会更好点，这样生物体选择阵型的时候就可以直接调用类，而不是调用方法，这个地方我觉得我需要重新想一下。