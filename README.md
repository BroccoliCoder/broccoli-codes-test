<h1>T3 Coding Challenge 1</h1>
<div class="custom-markdown steps-contents">
    <h2>Summary</h2>
    <p><em>Figure 3&ndash;79</em>
        <span>&nbsp;</span>shows an example page containing two applications of floating objects. In the first line of Lincoln&rsquo;s second inaugural speech a drop capital is created by floating the first letter of the first paragraph next to the surrounding text. The text of the speech is wrapped around the image of Lincoln using an irregular line wrap. This effect is created by cutting the Lincoln image into separate strips which are floated and stacked on top of each other. In this Coding Challenge you will explore how to create both effects.
    </p>
    <p>&nbsp;</p>
    <figure>
        <a class="markdown-image-link" title="Open image in a new tab" href="https://cdn.filestackcontent.com/FRTes321Qt2WWm1JDhgs" target="_blank" rel="noopener">
            <img src="https://cdn.filestackcontent.com/FRTes321Qt2WWm1JDhgs" alt="A webpage titled, &ldquo;Lincoln&rsquo;s second inaugural&rdquo; displays three paragraphs of content with an image of Lincoln at the right of the page. " />
        </a>
    </figure>
    <sup><em>Figure 3-79</em></sup>
    <p>&nbsp;</p>
    <p>Do the following:</p>
</div>
<div class="step-block-outer step-block--not-last">
    <div class="step-block-header" role="heading" aria-level="2"><strong>Tasks</strong></div>
    <div class="step-block-header" role="heading" aria-level="2">
        <span>Open the files&nbsp;</span><em>code3-1.html</em>
        <span>&nbsp;and&nbsp;</span><em>code3-1_float.css<span>&nbsp;</span></em>
        <span>and in the comment section enter your&nbsp;</span><strong>name</strong>
        <span>&nbsp;(First + Last) and the&nbsp;</span><strong>date</strong>
        <span>&nbsp;(MM/DD/YYYY) into the&nbsp;</span><code>Author:</code>
        <span>&nbsp;and&nbsp;</span><code>Date:</code>
        <span>&nbsp;fields of the file.</span>
    </div>
    <div class="step-block-header" role="heading" aria-level="2">
        <span>
            <br />Go to the&nbsp;<em>code3-1.html</em>&nbsp;file in your editor. Within the&nbsp;<code>head</code>&nbsp;section insert a&nbsp;<code>link</code>&nbsp;element linking the page to the&nbsp;<em>code3-1_float.css</em>&nbsp;style sheet file. Take some time to study the content of the page.
        </span>
    </div>
    <div class="step-block-header" role="heading" aria-level="2">
        <span>
            <br />Open the file&nbsp;<em>code3-1_float.css</em>, and for all&nbsp;<code>img</code>&nbsp;elements create a style rule to set the height of the image to&nbsp;<strong>3.3em</strong>. Float all&nbsp;<code>img</code>&nbsp;elements on the right margin, but only when the right margin is first cleared of any floats. (Hint:&nbsp;<code>clear: right</code>).
        </span>
    </div>
    <div class="step-block-header" role="heading" aria-level="2">
        <p>To create a drop cap insert a style rule for the selector<span>&nbsp;</span><code>p:first-of-type::first-letter</code>
            <span>&nbsp;</span>and add the following styles:
        </p>
        <ol>
            <li>Float the element on the left margin.</li>
            <li>Set the font size to<span>&nbsp;</span><strong>4em</strong>
                <span>&nbsp;</span>and the line height to<span>&nbsp;</span><strong>0.8em</strong>.
            </li>
            <li>Set the size of the right margin and padding space to<span>&nbsp;</span><strong>0.1em</strong>. Set the bottom padding to<span>&nbsp;</span><strong>0.2em</strong>.</li>
        </ol>
        <p>Display the first line of the speech in small caps by adding a style rule for the selector<span>&nbsp;</span><code>p:first-of-type::first-line</code>
            <span>&nbsp;</span>that changes the font variant to small-caps and the font size to<span>&nbsp;</span><strong>1.4em</strong>.
        </p>
        <p>
            <span>Open the page in the browser preview and verify the layout of the page resembles that shown in&nbsp;</span><em>Figure 3-79</em>
            <span>.</span>
        </p>
    </div>
</div>
