#AndroidCustomAd
Custom Advertisements in Android using MoPub

This is featured code from the blog post titled: [Android Custom Ad-MoPub Edition](http://www.letsthinkabout.us/post/android-custom-ad-mopub-edition)

<p align="center">
  <img src="https://raw.github.com/bbhsu2/AndroidCustomAd/master/homescrn.png?raw=true" alt="project image"/>
</p>

Be sure to add your own advertisement id from MoPub here in views.AdView:

    public AdView(Context context, AttributeSet attrs){
        super(context, attrs);
        this.context = context;
        //TODO: Set your own Ad Unit ID!
        this.setAdUnitId(""); 
        this.loadAd();
        this.setBannerAdListener(this);
    }

**In the XML Layout, declare the custom class**

    <views.AdView
        android:layout_width="fill_parent"
        android:layout_height="50dp" />

##Enjoy!
&copy; 2014 All Good People LLC
