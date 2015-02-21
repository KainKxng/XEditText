加强版的EditText,可以为DrawableLeft和DrawableRight设置点击事件

<p><strong>Demo</strong></p>

-------

<code>
<pre>
public class MainActivity extends Activity {
    private XEditText mPassword ;

    @Override
    protected void onCreate(Bundle saveInstance) {
        super.onCreate() ;
        setContentView(R.layout.main) ;
        
        mPassword.setDrawableRightListener(new DrawableRightListener() {            
            @Override
            public void onDrawableRightClick(View view) {
                // ÄãµÄ¾ßÌåÂß¼­
            }
        }) ;
    }
}
</pre>
</code>
