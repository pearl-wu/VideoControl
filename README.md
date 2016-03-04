# video_view

###open video
        VideoPlayer.play(
            str,
            {
               volume: 0.5,
               scalingMode: VideoPlayer.SCALING_MODE.SCALE_TO_FIT_WITH_CROPPING,
               videoWidth: 1280,
               videoHeight: 720,
               videoXx: 200,		// 0->水平置中
               videoYy: 0		// 0->垂直置中
            }
       );

###close video
        VideoPlayer.close();
