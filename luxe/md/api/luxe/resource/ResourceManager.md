
[![Logo](../../../images/logo.png)](../../../api/index.html)

---


<h1>ResourceManager</h1>
<small>`luxe.resource.ResourceManager`</small>



<hr/>

`class`<br/><span class="meta">
meta: @:keep</span>

<hr/>


&nbsp;
&nbsp;




<h3>Members</h3> <hr/><span class="member apipage">
                <a name="data"><a class="lift" href="#data">data</a></a><div class="clear"></div>
                <code class="signature apipage">data : [Map](http://api.haxe.org/Map.html)&lt;[String](http://api.haxe.org/String.html), [luxe.resource.DataResource](../../../api/luxe/resource/DataResource.html)&gt;</code><br/></span>
            <span class="small_desc_flat"></span><br/><span class="member apipage">
                <a name="fonts"><a class="lift" href="#fonts">fonts</a></a><div class="clear"></div>
                <code class="signature apipage">fonts : [Map](http://api.haxe.org/Map.html)&lt;[String](http://api.haxe.org/String.html), [phoenix.BitmapFont](../../../api/phoenix/BitmapFont.html)&gt;</code><br/></span>
            <span class="small_desc_flat"></span><br/><span class="member apipage">
                <a name="json"><a class="lift" href="#json">json</a></a><div class="clear"></div>
                <code class="signature apipage">json : [Map](http://api.haxe.org/Map.html)&lt;[String](http://api.haxe.org/String.html), [luxe.resource.JSONResource](../../../api/luxe/resource/JSONResource.html)&gt;</code><br/></span>
            <span class="small_desc_flat"></span><br/><span class="member apipage">
                <a name="render_textures"><a class="lift" href="#render_textures">render\_textures</a></a><div class="clear"></div>
                <code class="signature apipage">render\_textures : [Map](http://api.haxe.org/Map.html)&lt;[String](http://api.haxe.org/String.html), [phoenix.RenderTexture](../../../api/phoenix/RenderTexture.html)&gt;</code><br/></span>
            <span class="small_desc_flat"></span><br/><span class="member apipage">
                <a name="resourcelist"><a class="lift" href="#resourcelist">resourcelist</a></a><div class="clear"></div>
                <code class="signature apipage">resourcelist : [Array](http://api.haxe.org/Array.html)&lt;[luxe.resource.Resource](../../../api/luxe/resource/Resource.html)&gt;</code><br/></span>
            <span class="small_desc_flat"></span><br/><span class="member apipage">
                <a name="shaders"><a class="lift" href="#shaders">shaders</a></a><div class="clear"></div>
                <code class="signature apipage">shaders : [Map](http://api.haxe.org/Map.html)&lt;[String](http://api.haxe.org/String.html), [phoenix.Shader](../../../api/phoenix/Shader.html)&gt;</code><br/></span>
            <span class="small_desc_flat"></span><br/><span class="member apipage">
                <a name="sounds"><a class="lift" href="#sounds">sounds</a></a><div class="clear"></div>
                <code class="signature apipage">sounds : [Map](http://api.haxe.org/Map.html)&lt;[String](http://api.haxe.org/String.html), [luxe.resource.SoundResource](../../../api/luxe/resource/SoundResource.html)&gt;</code><br/></span>
            <span class="small_desc_flat"></span><br/><span class="member apipage">
                <a name="stats"><a class="lift" href="#stats">stats</a></a><div class="clear"></div>
                <code class="signature apipage">stats : [luxe.resource.ResourceStats](../../../api/luxe/resource/ResourceStats.html)</code><br/></span>
            <span class="small_desc_flat"></span><br/><span class="member apipage">
                <a name="text"><a class="lift" href="#text">text</a></a><div class="clear"></div>
                <code class="signature apipage">text : [Map](http://api.haxe.org/Map.html)&lt;[String](http://api.haxe.org/String.html), [luxe.resource.TextResource](../../../api/luxe/resource/TextResource.html)&gt;</code><br/></span>
            <span class="small_desc_flat"></span><br/><span class="member apipage">
                <a name="textures"><a class="lift" href="#textures">textures</a></a><div class="clear"></div>
                <code class="signature apipage">textures : [Map](http://api.haxe.org/Map.html)&lt;[String](http://api.haxe.org/String.html), [phoenix.Texture](../../../api/phoenix/Texture.html)&gt;</code><br/></span>
            <span class="small_desc_flat"></span><br/>


<h3>Methods</h3> <hr/><span class="method apipage">
            <a name="add"><a class="lift" href="#add">add</a></a><div class="clear"></div>
            <code class="signature apipage">add(res:[luxe.resource.Resource](../../../api/luxe/resource/Resource.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="cache"><a class="lift" href="#cache">cache</a></a><div class="clear"></div>
            <code class="signature apipage">cache(res:[luxe.resource.Resource](../../../api/luxe/resource/Resource.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="clear"><a class="lift" href="#clear">clear</a></a><div class="clear"></div>
            <code class="signature apipage">clear(and\_persistent:[Bool](http://api.haxe.org/Bool.html)<span>=false</span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="find"><a class="lift" href="#find">find</a></a><div class="clear"></div>
            <code class="signature apipage">find(id:[String](http://api.haxe.org/String.html)<span></span>) : [luxe.resource.Resource](../../../api/luxe/resource/Resource.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="find_data"><a class="lift" href="#find_data">find\_data</a></a><div class="clear"></div>
            <code class="signature apipage">find\_data(\_name:[String](http://api.haxe.org/String.html)<span></span>) : [Null](http://api.haxe.org/Null.html)&lt;[luxe.resource.DataResource](../../../api/luxe/resource/DataResource.html)&gt;</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="find_font"><a class="lift" href="#find_font">find\_font</a></a><div class="clear"></div>
            <code class="signature apipage">find\_font(\_name:[String](http://api.haxe.org/String.html)<span></span>) : [Null](http://api.haxe.org/Null.html)&lt;[phoenix.BitmapFont](../../../api/phoenix/BitmapFont.html)&gt;</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="find_json"><a class="lift" href="#find_json">find\_json</a></a><div class="clear"></div>
            <code class="signature apipage">find\_json(\_name:[String](http://api.haxe.org/String.html)<span></span>) : [Null](http://api.haxe.org/Null.html)&lt;[luxe.resource.JSONResource](../../../api/luxe/resource/JSONResource.html)&gt;</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="find_render_texture"><a class="lift" href="#find_render_texture">find\_render\_texture</a></a><div class="clear"></div>
            <code class="signature apipage">find\_render\_texture(\_name:[String](http://api.haxe.org/String.html)<span></span>) : [Null](http://api.haxe.org/Null.html)&lt;[phoenix.RenderTexture](../../../api/phoenix/RenderTexture.html)&gt;</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="find_shader"><a class="lift" href="#find_shader">find\_shader</a></a><div class="clear"></div>
            <code class="signature apipage">find\_shader(\_name:[String](http://api.haxe.org/String.html)<span></span>) : [Null](http://api.haxe.org/Null.html)&lt;[phoenix.Shader](../../../api/phoenix/Shader.html)&gt;</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="find_sound"><a class="lift" href="#find_sound">find\_sound</a></a><div class="clear"></div>
            <code class="signature apipage">find\_sound(\_name:[String](http://api.haxe.org/String.html)<span></span>) : [Null](http://api.haxe.org/Null.html)&lt;[luxe.resource.SoundResource](../../../api/luxe/resource/SoundResource.html)&gt;</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="find_text"><a class="lift" href="#find_text">find\_text</a></a><div class="clear"></div>
            <code class="signature apipage">find\_text(\_name:[String](http://api.haxe.org/String.html)<span></span>) : [Null](http://api.haxe.org/Null.html)&lt;[luxe.resource.TextResource](../../../api/luxe/resource/TextResource.html)&gt;</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="find_texture"><a class="lift" href="#find_texture">find\_texture</a></a><div class="clear"></div>
            <code class="signature apipage">find\_texture(\_name:[String](http://api.haxe.org/String.html)<span></span>) : [Null](http://api.haxe.org/Null.html)&lt;[phoenix.Texture](../../../api/phoenix/Texture.html)&gt;</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="new"><a class="lift" href="#new">new</a></a><div class="clear"></div>
            <code class="signature apipage">new() : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="remove"><a class="lift" href="#remove">remove</a></a><div class="clear"></div>
            <code class="signature apipage">remove(res:[luxe.resource.Resource](../../../api/luxe/resource/Resource.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>
<span class="method apipage">
            <a name="uncache"><a class="lift" href="#uncache">uncache</a></a><div class="clear"></div>
            <code class="signature apipage">uncache(res:[luxe.resource.Resource](../../../api/luxe/resource/Resource.html)<span></span>) : [Void](http://api.haxe.org/Void.html)</code><br/><span class="small_desc_flat"></span>


</span>



<hr/>

&nbsp;
&nbsp;
&nbsp;
&nbsp;