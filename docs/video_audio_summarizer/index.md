# Video/Audio Summarizer

A Streamlit-based application that creates concise summary of a video or audio. User can input a Youtube link or upload their own audio/video. 
Next, implementing LLM functionality a summary with timestamps is generated. User can directly jump to sections of an audio/video extracted by model using generated buttons.

The application is deployed on Streamlit Community Cloud. Due to YouTube API restrictions and IP-based limitations in cloud environments, automatic caption retrieval is currently blocked. As a workaround, users may upload a file manually or run the application locally.
 
<a href="https://github.com/maciwid/video_audio_summary" class="md-button md-button--primary">GitHub Repo</a>
<a href="https://videoaudiosummary-bi2nnfae5v9h7seam2qwag.streamlit.app/" class="md-button md-button--primary">Streamlit Community Cloud </a>

### Screenshots:
![Screenshot 1](images/1.png)
![Screenshot 2](images/2.png)
![Screenshot 3](images/3.png)
![Screenshot 4](images/4.png)


<!-- <iframe
    id="content"
    src="iris.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe> -->
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>
