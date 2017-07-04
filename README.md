# Springy_Facebook_Rebound


![ic_launcher](https://user-images.githubusercontent.com/11782272/27817284-ec04cbb0-60ad-11e7-901e-88e261b60c86.png)

  Springy is About Motion and Animation on Android platform, you can make smooth and clean property animations
### Scale, Translate, Alpha, Rotate.

![media player](https://user-images.githubusercontent.com/11782272/27817251-c255cff8-60ad-11e7-8e39-4e1c5eda1865.gif)    



## How to use

   Create Springy Animator instance and you can initialize by one of it's two constructor 
     
     with Spring Config.
     
     1.SpringyAnimator(SpringAnimationType.SCALEXY,TENSION, FRACTION, ANIMATION_START_VALUE, ANIMATION_END_VALUE); 
     
     Without Spring Config.
     
     2.SpringyAnimator(SpringAnimationType.SCALEXY, ANIMATION_START_VALUE, ANIMATION_END_VALUE);
     
            {
            
            SpringyAnimator iconSpring = new SpringyAnimator(SpringAnimationType.SCALEXY, 4, 2.5, 0, 1);
            iconSpring.setDelay(200);
            iconSpring.startSpring(myView);
      
            }
    

![recylcer view](https://user-images.githubusercontent.com/11782272/27817252-c3d078b0-60ad-11e7-9cab-8a2ff4fe80c6.gif)





## About Facebook Rebound

<a href="http://facebook.github.io/rebound">Rebound</a> is a java library that
models spring dynamics. Rebound spring models can be used to create animations
that feel natural by introducing real world physics to your application.

Rebound is not a general purpose physics library; however, spring dynamics
can be used to drive a wide variety of animations. The simplicity of Rebound
makes it easy to integrate and use as a building block for creating more
complex components like pagers, toggles, and scrollers.

For examples and usage instructions head over to:

[facebook.github.io/rebound](http://facebook.github.io/rebound)
