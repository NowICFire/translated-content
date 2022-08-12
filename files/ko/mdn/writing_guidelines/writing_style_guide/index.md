---
title: MDN 스타일 가이드
slug: MDN/Writing_guidelines/Writing_style_guide
tags:
  - Documentation
  - Guide
  - MDN
  - MDN Meta
  - MDN 스타일 가이드
  - 스타일 가이드
  - 스타일 가이드 작성
translation_of: MDN/Guidelines/Writing_style_guide
original_slug: MDN/Guidelines/Writing_style_guide
---
<div>{{MDNSidebar}}</div>

<div>{{IncludeSubnav("/ko/docs/MDN")}}</div>

<p>정돈되고 일관적이며 읽기 쉬운 문서를 제공하고자, MDN 웹 문서 스타일 안내서는 글의 정렬, 철자, 서식 방법 등을 정리합니다. 이 가이드는 엄격한 규칙이라기보다 가이드라인입니다. 우리는 형식보다는 내용에 더 관심이 있습니다. 그러니 기여하기 전에 스타일 가이드를 배워야 한다는 부담을 느끼시지 않아도 됩니다. 하지만 나중에 다른 부지런한 지원자가 이 가이드를 따라 당신의 작업물을 편집할 수 있습니다. 만약 그런 일이 벌어지더라도 화내거나 놀라지 마세요.</p>

<p>이 가이드의 언어적 측면의 내용은 영문을 위주로 작성되었습니다. 기타 다른 언어는 언어만의 고유한 스타일 가이드를 가질 수 있으며, 새롭게 만드는 것도 좋습니다. 이 페이지들은 지역화 팀 페이지의 하위 페이지로 생성되어야 합니다.</p>

<p>MDN이 아닌 다른 사이트를 위해 쓰여진 콘텐츠를 적용하는 스타일 표준에 대한 내용은 <a href="https://www.mozilla.org/en-US/styleguide/">One Mozilla 스타일 가이드</a>를 참고하세요.</p>

<h2 id="Page_name_and_heading_capitalization" name="Page_name_and_heading_capitalization">기본</h2>

<p>아무리 방대한 문서화 스타일 가이드라도 가장 기본적인 텍스트 표준에서 시작하는 것이 좋습니다. 텍스트 표준은 일관된 문서화를 유지하는데 도움을 줍니다. 이어지는 섹션에서 도움이 될 만한 이런 기본들을 설명합니다.</p>

<h3 id="페이지_제목">페이지 제목</h3>

<p>페이지 제목은 검색 결과에 사용되며, 페이지 상단의 페이지 이동 경로(breadcrumb) 목록에 페이지 계층 구조를 구성하는 데 사용됩니다.  (페이지 상단과 검색 결과 상단에 표시되는) 페이지 제목은 페이지 "슬러그"와 다를 수 있습니다. "슬러그"는 페이지 URL의 일부로   "<em>&lt;locale&gt;/docs/</em>" 다음에 따라오는 부분입니다.</p>

<h4 id="제목과_섹션제목_대문자넣기Capitalization"> 제목과  섹션제목 대문자넣기(Capitalization)</h4>

<p>페이지 타이틀과 섹션 제목은 헤드라인 스타일 대문자넣기보다는 (첫번째 단어와 필요한 명사만 대문자를 넣는 방식의)일반 문장 스타일 대문자넣기를 해야 합니다:</p>

<ul>
 <li><strong>Correct</strong>: "A new method for creating JavaScript rollovers"</li>
 <li><strong>Incorrect</strong>: "A New Method for Creating JavaScript Rollovers"</li>
</ul>

<p>이런 스타일 규칙이 적용되기 전에 작성된 수많은 예전 문서들이 현재도 존재합니다. 자유롭게 해당 문서들을 수정해도 좋습니다. 우리는 점차적으로 스타일 규칙을 맞춰 나갈겁니다.</p>

<h4 id="제목_및_슬러그slug_선택하기">제목 및 슬러그(slug) 선택하기</h4>

<p>페이지 슬러그는 짧게 만들어야 합니다. 새로운 레벨의 계층을 만들때, 그 레벨의 요소는 슬러그에서 한,두 단어로 표현되어야 합니다.</p>

<p>반면에, 페이지 제목은 ,합리적인 범위내에서, 당신이 원하는 만큼 길어도 됩니다. 그리고 구체적이어야 합니다.</p>

<h4 id="신규_서브트리_생성하기">신규 서브트리 생성하기</h4>

<p>어떤 토픽이나 주제 영역에 대한 문서를 추가할 필요가 있다면, 당신이 선택할 일반적인 방법은 랜딩 페이지를 생성한 이후, 각각의 개별적인 문서의 서브페이지를 추가하는 것입니다. 랜딩 페이지는 토픽이나 기술을 설명하는 한두 개의 문단으로 시작한 이후, 각 페이지의 설명이 달린 서브페이지의 목록을 전달해야합니다. 우리가 개발한 몇가지 매크로로 페이지를 목록에 자동으로 삽입할 수 있습니다.</p>

<p>예를 들면 , 아래와 같이 구성된 <a href="/ko/docs/Web/JavaScript">자바스크립트</a> 가이드를 생각해봅시다.</p>

<ul>
 <li><a href="/ko/docs/Web/JavaScript/Guide" title="JavaScript/Guide">JavaScript/안내서</a> - 주 목차 페이지</li>
 <li><a href="/ko/docs/Web/JavaScript/Guide/소개" title="JavaScript/Guide/JavaScript_Overview">JavaScript/안내서/JavaScript 소</a>개</li>
 <li><a href="/ko/docs/Web/JavaScript/Guide/함수" title="JavaScript/Guide/Functions">JavaScript/안내서/함수</a></li>
 <li><a href="/ko/docs/Web/JavaScript/Guide/객체_모델의_세부사항" title="JavaScript/Guide/Details_of_the_Object_Model">JavaScript/안내서/객체 모델의 세부사항</a></li>
</ul>

<p>문서를 문서구조 최상층에 두는 것은 최대한 피해야 합니다. 이렇게 하면 사이트가 느려지며, 사이트 탐색과 네비게이션을 비효율적으로 만듭니다.</p>

<div class="blockIndicator note">
<p>주목할 점: 문서 추가는 <a href="/ko/docs/MDN/Contribute/Howto/Create_and_edit_pages#Getting_page-creation_permissions">페이지 생성 권한</a>이 필요합니다.</p>
</div>

<h3 id="General_article_content_guidelines">General article content guidelines</h3>

<p>When writing any document, it's important to know how much to say. If you ramble on too long, or provide excessive detail, the article becomes tedious to read and nobody will use it. Getting the amount of coverage right is important for several reasons. Among those reasons: to ensure that the reader finds the information they truly need, and to provide enough quality material for search engines to adequately analyze and rank the article.</p>

<p>We'll discuss the former (providing the information the reader may need) here. To learn a little about ensuring that pages are properly classified and ranked by search engines, see the article <a href="/en-US/docs/MDN/Contribute/Howto/Write_for_SEO">How to write for SEO on MDN</a>.</p>

<p>The goal is to write pages that include all the information that readers may need without going on too long about it all. We have a few recommendations in this area.</p>

<h4 id="Consider_your_audience">Consider your audience</h4>

<p>Keep in mind that these are guidelines. Some of these tips may not apply in every case. Certainly keep your article's audience in mind. An article on advanced network techniques likely doesn't need to go into as much detail about basic networking concepts as the typical article on networking code, for instance.</p>

<h4 id="Provide_a_useful_summary">Provide a useful summary</h4>

<p>Make sure the article's summary—that is, the opening paragraph or paragraphs before the first heading—provides enough information for the reader to understand if the article is likely to be covering what they're interested in reading about.</p>

<p>In guide or tutorial content, the summary should let the reader know what topics will be covered and what they're already expected to know, if anything. It should mention the technology, technologies, and/or APIs that are being documented or discussed, with links to those, and it should offer hints as to the situations in which the article's contents might be useful.</p>

<h5 id="Example_Too_short!">Example: Too short!</h5>

<p>This example of a summary is far too short. It leaves out too much information, such as what it means exactly to "stroke" text, where the text is drawn, and so forth.</p>

<div class="example-bad"><strong><code>CanvasRenderingContext2D.strokeText()</code></strong> draws a string.</div>

<h5 id="Example_Too_long!">Example: Too long!</h5>

<p>Here, we've updated the summary, but now it's far too long. Too much detail is included, and the text gets far too much into other methods and properties.</p>

<p>Instead, the summary should focus on the <code>strokeText()</code> method, and should refer to the appropriate guide where the other details are offered.</p>

<div class="example-bad">
<p>When called, the Canvas 2D API method <code><strong>CanvasRenderingContext2D.strokeText()</strong></code> strokes the characters in the specified string beginning at the coordinates specified, using the current pen color.In the terminology of computer graphics, "stroking" text means to draw the outlines of the glyphs in the string without filling in the contents of each character with color.</p>

<p>The text is drawn using the context's current font as specified in the context's {{domxref("CanvasRenderingContext2D.font", "font")}} property.</p>

<p>The placement of the text relative to the specified coordinates are determined by the context's <code>textAlign</code>, <code>textBaseline</code>, and <code>direction</code> properties. <code>textAlign</code> controls the placement of the string relative to the X coordinate specified; if the value is <code>"center"</code>, then the string is drawn starting at <code>x - (stringWidth / 2)</code>, placing the specified X-coordinate in the middle of the string. If the value is <code>"left"</code>, the string is drawn starting at the specified value of <code>x</code>. And if <code>textAlign</code> is <code>"right"</code>, the text is drawn such that it ends at the specified X-coordinate.</p>

<p>(etc etc etc...)</p>

<p>You can, optionally, provide a fourth parameter that lets you specify a maximum width for the string, in pixels. If you provide this parameter, the text is compressed horizontally or scaled (or otherwise adjusted) to fit inside a space that wide when being drawn.</p>

<p>You can call the <strong><code>fillText()</code></strong> method to draw a string's characters as filled with color instead of only drawing the outlines of the characters.</p>
</div>

<h5 id="Example_Much_better!">Example: Much better!</h5>

<p>Here we see a much better overview for the <code>strokeText()</code> method.</p>

<div class="example-good">
<p>The {{domxref("CanvasRenderingContext2D")}} method <code><strong>strokeText()</strong></code>, part of the <a href="/en-US/docs/Web/API/Canvas_API">Canvas 2D API</a>, strokes—that is, draws the outlines of—the characters of a specified string, anchored at the position indicated by the given X and Y coordinates. The text is drawn using the context's current {{domxref("CanvasRenderingContext2D.font", "font")}}, and is justified and aligned according to the {{domxref("CanvasRenderingContext2D.textAlign", "textAlign")}}, {{domxref("CanvasRenderingContext2D.textBaseline", "textBaseline")}}, and {{domxref("CanvasRenderingContext2D.direction", "direction")}} properties.</p>

<p>For more details and further examples, see {{SectionOnPage("/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Drawing_graphics", "Text")}} in the Learning Area as well as our main article on the subject, <a href="/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text">Drawing text</a>.</p>
</div>

<h4 id="Include_all_relevant_examples">Include all relevant examples</h4>

<p>More pages should have examples than not. The majority of pages probably deserve multiple examples, in fact.</p>

<p>It's important to ensure that you use examples to clarify what every parameter is used for, and to clarify any edge cases that may exist. You should also use examples to demonstrate solutions for common tasks, and you should use examples to demonstrate solutions to problems that may arise.</p>

<p>Each example should be preceded by text explaining what the example does and anything the reader should know before beginning to read or try out the example.</p>

<h5 id="Code_Examples">Code Examples</h5>

<p>Each piece of code should include an explanation of how it works. Keep in mind that it may make sense to break up a large piece of code into smaller portions so they can be described individually.</p>

<p>The text following each piece of code should explain anything relevant, using an appropriate level of detail.</p>

<ul>
 <li>If the code is very simple and doesn't really feature anything directly related to the API being documented, you may only give a quick summary of what it is and why it's there.</li>
 <li>If the code is intricate, uses the API being documented, or is technically creative, you should provide a more detailed explanation.</li>
</ul>

<p>When using the live sample system, it's helpful to be aware that all of the {{HTMLElement("pre")}} blocks in the area that contains the sample are concatenated together before running the example, which lets you break any or all of the HTML, CSS, and JavaScript into multiple segments, each optionally with its own descriptions, headings, and so forth. This makes documenting code incredibly powerful and flexible.</p>

<h4 id="Overly-short_articles_are_hard_to_find">Overly-short articles are hard to find</h4>

<p>If an article is "thin"—that is, too short—it may not be indexed properly (or at all) by search engines. As a rule of thumb, the article's body text should be at least 250–300 words. Don't artificially inflate a page, but treat this guideline as a minimum target length when possible.</p>

<h3 id="Sections_paragraphs_and_newlines">Sections, paragraphs, and newlines</h3>

<p>Use heading levels in decreasing order: {{HTMLElement("h2")}} then {{HTMLElement("h3")}} then {{HTMLElement("h4")}}, without skipping levels.</p>

<p>H2 is the highest level allowed because H1 is reserved for the page title. If you need more than three or four levels of headers, consider breaking up the article into several smaller articles with a landing page, and linking them together using the following macros: <code>\{{Next}}</code>, <code>\{{Previous}}</code>, and <code>\{{PreviousNext}}</code>.</p>

<h4 id="Heading_dos_and_donts">Heading dos and donts</h4>

<ul>
 <li>Don't create single subsections. Don't subdivide a topic into a single subtopic. It's either two subheadings or more, or none at all.</li>
 <li>Don't use styles and classes within headings. This includes the {{HTMLElement("code")}} element for code terms. So don't make a heading "Using the <code>SuperAmazingThing</code> interface". It should instead just be "Using the SuperAmazingThing interface".</li>
 <li>Avoid using macros within headings (except for certain macros that are specifically designed to be used in headings).</li>
 <li>Don't create "bumping heads." These are headings followed immediately by a subheading, with no content text in between. This doesn't look good, and leaves readers without any explanatory text at the beginning of the outer section.</li>
</ul>

<p>The <kbd>Enter</kbd> (or <kbd>Return</kbd>) key on your keyboard starts a new paragraph. To insert a newline, rather than a new paragraph (that is, to create a {{HTMLElement("br")}} instead of a {{HTMLElement("p")}}), hold down the <kbd>Shift</kbd> key while pressing <kbd>Enter</kbd>.</p>

<h3 id="Lists">Lists</h3>

<p>Lists should be formatted and structured uniformly across all contributions. Individual list items should be written with suitable punctuation, regardless of the list format. However, depending on the type of list you are creating, you will want to adjust your writing as described in the sections below.</p>

<h4 id="Bulleted_lists">Bulleted lists</h4>

<p>Bulleted lists should be used to group related pieces of concise information. Each item in the list should follow a similar sentence structure. Phrases and sentences in bulleted lists should include standard punctuation. Periods must appear at the end of each sentence in a bulleted list, including the item's final sentence, just as would be expected in a paragraph.</p>

<p>An example of a correctly structured bulleted list:</p>

<div class="example-good">
<p>In this example we should include:</p>

<ul>
 <li>A condition, with a brief explanation.</li>
 <li>A similar condition, with a brief explanation.</li>
 <li>Yet another condition, with some further explanation.</li>
</ul>
</div>

<p>Note how the same sentence structure repeats from bullet to bullet. In this example, each bullet point states a condition followed by a comma and a brief explanation, and each item in the list ends with a period.</p>

<h4 id="Numbered_lists">Numbered lists</h4>

<p>Numbered lists are used primarily to enumerate steps in a set of instructions. Because instructions can be complex, clarity is a priority, especially if the text in each list item is lengthy. As with bulleted lists, follow standard punctuation usage.</p>

<p>An example of a correctly structured numbered list:</p>

<div class="example-good">
<p>In order to correctly structure a numbered list, you should:</p>

<ol>
 <li>Open with a heading or brief paragraph to introduce the instructions. It's important to provide the user with context before beginning the instructions.</li>
 <li>Start creating your instructions, and keep each step in its own numbered item. Your instructions may be quite extensive, so it is important to write clearly and use correct punctuation.</li>
 <li>After you have finished your instructions, close off the numbered list with a brief summary or explanation of the expected outcome upon completion.</li>
</ol>

<p>This is an example of writing a closing explanation. We have created a short numbered list that provides instructive steps to produce a numbered list with the correct formatting.</p>
</div>

<p>Note how the items in numbered lists read like short paragraphs. Because numbered lists are routinely used for instructional purposes, or to walk someone through an orderly procedure, be sure to keep each item focused: one item per number or step.</p>

<h3 id="Text_formatting_and_styles">Text formatting and styles</h3>

<p>Use the <strong>"Formatting Styles"</strong> drop-down list to apply predefined styles to selected content.</p>

<div class="blockIndicator note">
<p>The <strong>"Note Box"</strong> style is used to call out important notes, like this one.</p>
</div>

<div class="blockIndicator warning">
<p>Similarly, the <strong>"Warning Box"</strong> style creates warning boxes like this.</p>
</div>

<p>Unless specifically instructed to do so, <em>do not</em> use the HTML <code>style</code> attribute to manually style content. If you can't do it using a predefined class, ask for help in the <a href="https://discourse.mozilla.org/c/mdn">MDN discussion forum</a>.</p>

<h3 id="Code_sample_style_and_formatting">Code sample style and formatting</h3>

<div class="blockIndicator note">
<p><strong>Note</strong>: This section deals with the styling/formatting of code as it appears on an MDN article. If you want guidelines on actually writing code examples, see our <a href="/en-US/docs/MDN/Contribute/Guidelines/Code_samples">Code sample guidelines</a>.</p>
</div>

<h4 id="Tabs_and_line_breaks">Tabs and line breaks</h4>

<p>Use two spaces per tab in all code examples. Indent the code cleanly, with open-brace ("<code>{</code>") characters on the same line as the statement that opens the block. For example:</p>

<pre class="notranslate">if (condition) {
  /* handle the condition */
} else {
  /* handle the "else" case */
}
</pre>

<p>Long lines shouldn't be allowed to stretch off horizontally to the extent that they require horizontal scrolling to read. Instead, break at natural breaking points. Some examples follow:</p>

<pre class="notranslate">if (class.CONDITION || class.OTHER_CONDITION || class.SOME_OTHER_CONDITION
       || class.YET_ANOTHER_CONDITION ) {
  /* something */
}

var toolkitProfileService = Components.classes["@mozilla.org/toolkit/profile-service;1"]
                           .createInstance(Components.interfaces.nsIToolkitProfileService);
</pre>

<h4 id="Inline_code_formatting">Inline code formatting</h4>

<p>Use the "Code" button (labeled with two angle brackets "&lt;&gt;") to apply inline code-style formatting to function names, variable names, and method names. (This uses the {{HTMLElement("code")}} element). For example: "the <code>frenchText()</code> function".</p>

<p>Method names should be followed by a pair of parentheses: <code>doSomethingUseful()</code>. The parentheses help differentiate methods from other code terms.</p>

<h4 id="Syntax_highlighting">Syntax highlighting</h4>

<p><img alt="Screenshot of the 'Syntax Highlighter' menu." src="https://mdn.mozillademos.org/files/12682/Language%20list.png" style="float: right;">Entire lines (or multiple lines) of code should be formatted using syntax highlighting rather than the {{HTMLElement("code")}} element. Select the appropriate language from the language list button (the one with the two code blocks), as seen in the screenshot to the right. This will insert a preformatted code box with line numbers and syntax highlighting for the chosen language.</p>

<div class="blockIndicator note">
<p><strong>Note:</strong> <em>Do not</em> use the {{HTMLElement("code")}} element inside the {{HTMLElement("pre")}} block!</p>

<p>While this structure is used on some sites, we do not do so on MDN; nesting these elements will break certain aspects of our styling.</p>
</div>

<p>The following example shows text with JavaScript formatting:</p>

<pre class="notranslate">for (let i = 0, j = 9; i &lt;= 9; i++, j--)
  document.writeln("a[" + i + "][" + j + "]= " + a[i][j]);</pre>

<p>If no appropriate language is available, use ("No Highlight" in the language menu). This will result in code without syntax highlighting:</p>

<pre class="notranslate">x = 42;</pre>

<h4 id="Syntax_definitions">Syntax definitions</h4>

<p>When writing the syntax description section of a reference page, use the <em>"Syntax Box"</em> option in the <strong>"Styles"</strong> drop-down menu in the editor toolbar. This creates a specially-formatted box used specifically for syntax definitions, distinguishing them from other code blocks.</p>

<h4 id="Blocks_not_referring_to_code">Blocks not referring to code</h4>

<p>There are a few use cases where a <code>&lt;pre&gt;</code> block does not refer to code and doesn't have syntax highlighting nor line numbers. In such cases you should add a <code>&lt;pre&gt;</code> without a <code>class</code> attribute. Those cases include things like tree structures:</p>

<pre class="notranslate">root/

  folder1/
    file1

  folder2/
    file2
    file3
</pre>

<p>To create preformatted content without syntax highlighting and line numbers click the "pre" button in the toolbar. Then start to type the text.</p>

<h4 id="Styling_mentions_of_HTML_elements">Styling mentions of HTML elements</h4>

<p>There are specific rules to follow when writing about HTML elements. These rules produce consistent descriptions of elements and their components. They also ensure correct linking to detailed documentation.</p>

<dl>
 <dt>Element names</dt>
 <dd>Use the <code>\{{HTMLElement}}</code> macro, which creates a link to the page for that element. For example, writing \{{HTMLElement("title")}} produces "{{HTMLElement("title")}}". If you don't want to create a link, <strong>enclose the name in angle brackets</strong> and use the "Inline Code" style (e.g., <code>&lt;title&gt;</code>).</dd>
 <dt>Attribute names</dt>
 <dd>Use "Inline Code" style to put attribute names in <code>code font</code>. Additionally, put them in <strong><code>bold face</code></strong> when the attribute is mentioned in association with an explanation of what it does, or the first time it's used in the article.</dd>
 <dt>Attribute definitions</dt>
 <dd>Use the <code>\{{htmlattrdef}}</code> macro (e.g., \{{htmlattrdef("type")}}) for the definition term, so that it can be linked to from other pages easily by simply using the <code>\{{htmlattrxref}}</code> macro (e.g., \{{htmlattrxref("attr","element")}}) to reference attribute definitions.</dd>
 <dt>Attribute values</dt>
 <dd>Use the "Inline Code" style to apply <code>&lt;code&gt;</code> to attribute values, and don't use quotation marks around string values, unless needed by the syntax of a code sample.</dd>
 <dd>For example: "When the <code>type</code> attribute of an <code>&lt;input&gt;</code> element is set to <code>email</code> or <code>tel</code> ..."</dd>
</dl>

<h3 id="Latin_abbreviations">Latin abbreviations</h3>

<h4 id="In_notes_and_parentheses">In notes and parentheses</h4>

<ul>
 <li>Common Latin abbreviations (etc., i.e., e.g.) may be used in parenthetical expressions and notes. Use periods in these abbreviations, followed by a comma or other appropriate punctuation.
  <ul>
   <li><strong>Correct</strong>: Web browsers (e.g., Firefox) can be used ...</li>
   <li><strong>Incorrect</strong>: Web browsers e.g. Firefox can be used ...</li>
   <li><strong>Incorrect</strong>: Web browsers, e.g. Firefox, can be used ...</li>
   <li><strong>Incorrect</strong>: Web browsers, (eg: Firefox) can be used ...</li>
  </ul>
 </li>
</ul>

<h4 id="In_running_text">In running text</h4>

<ul>
 <li>In regular text (i.e., text outside of notes or parentheses), use the English equivalent of the abbreviation.
  <ul>
   <li><strong>Correct</strong>: ... web browsers, and so on.</li>
   <li><strong>Incorrect</strong>: ... web browsers, etc.</li>
   <li><strong>Correct</strong>: Web browsers such as Firefox can be used ...</li>
   <li><strong>Incorrect</strong>: Web browsers e.g. Firefox can be used ...</li>
  </ul>
 </li>
</ul>

<h4 id="Meanings_and_English_equivalents_of_Latin_abbreviations">Meanings and English equivalents of Latin abbreviations</h4>

<table>
 <thead>
  <tr>
   <th scope="col">Abbrev</th>
   <th scope="col">Latin</th>
   <th scope="col">English</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>cf.</td>
   <td><em>confer</em></td>
   <td>compare</td>
  </tr>
  <tr>
   <td>e.g.</td>
   <td><em>exempli gratia</em></td>
   <td>for example</td>
  </tr>
  <tr>
   <td>et al.</td>
   <td><em>et alii</em></td>
   <td>and others</td>
  </tr>
  <tr>
   <td>etc.</td>
   <td><em>et cetera</em></td>
   <td>and so forth, and so on</td>
  </tr>
  <tr>
   <td>i.e.</td>
   <td><em>id est</em></td>
   <td>that is, in other words</td>
  </tr>
  <tr>
   <td>N.B.</td>
   <td><em>nota bene</em></td>
   <td>note well</td>
  </tr>
  <tr>
   <td>P.S.</td>
   <td><em>post scriptum</em></td>
   <td>postscript</td>
  </tr>
 </tbody>
</table>

<div class="blockIndicator note">
<p>Always consider whether it's truly beneficial to use a Latin abbreviation. Some of these are used so rarely that many readers won't understand the meaning, and others are often confused with one another.</p>

<p>Also, be sure that <em>you</em> use them correctly, if you choose to do so. For example, be careful not to confuse "e.g." with "i.e.", which is a common error.</p>
</div>

<h3 id="Acronyms_and_abbreviations">Acronyms and abbreviations</h3>

<h4 id="Capitalization_and_periods">Capitalization and periods</h4>

<p>Use full capitals and delete periods in all acronyms and abbreviations, including organizations such as "US" and "UN".</p>

<ul>
 <li><strong>Correct</strong>: XUL</li>
 <li><strong>Incorrect</strong>: X.U.L.; Xul</li>
</ul>

<h4 id="Expansion">Expansion</h4>

<p>On the first mention of a term on a page, expand acronyms likely to be unfamiliar to users. When in doubt, expand it, or, better, link it to the article or <a href="/en-US/docs/Glossary">glossary</a> entry describing the technology.</p>

<ul>
 <li><strong>Correct</strong>: "XUL (XML User Interface Language) is Mozilla's XML-based language..."</li>
 <li><strong>Incorrect</strong>: "XUL is Mozilla's XML-based language..."</li>
</ul>

<h4 id="Plurals_of_acronyms_and_abbreviations">Plurals of acronyms and abbreviations</h4>

<p>For plurals of acronyms or abbreviations, add <em>s</em>. Don't use an apostrophe. Ever. Please.</p>

<ul>
 <li><strong>Correct</strong>: CD-ROMs</li>
 <li><strong>Incorrect</strong>: CD-ROM's</li>
</ul>

<h4 id="Versus_vs._and_v.">"Versus", "vs.", and "v."</h4>

<p>The contraction "vs." is preferred.</p>

<ul>
 <li><strong>Correct</strong>: this vs. that</li>
 <li><strong>Incorrect</strong>: this v. that</li>
 <li><strong>Incorrect</strong>: this versus that</li>
</ul>

<h3 id="Capitalization">Capitalization</h3>

<p>Use standard English capitalization rules in body text, and capitalize "World Wide Web." It is acceptable to use lower case for "web" (used alone or as a modifier) and "internet".</p>

<div class="blockIndicator note">
<p>This guideline is a change from a previous version of this guide, so you may find many instances of "Web" and "Internet" on MDN.</p>

<p>Feel free to change these as you are making other changes, but editing an article just to change capitalization is not necessary.</p>
</div>

<p>Keyboard keys should use sentence-style capitalization, not all-caps capitalization. For example, "<kbd>Enter</kbd>" not "<kbd>ENTER</kbd>." The only exception is that if you wish to abbreviate the name of the "<kbd>Escape</kbd>" key, you may use "<kbd>ESC</kbd>".</p>

<p>Certain words should always be capitalized (such as trademarks which include capital letters), or words derived from the name of a person (unless it's being used within code, and the rules of the language in which the code is written mandate lower-casing). Some examples:</p>

<ul>
 <li>Boolean (named for English mathematician and logician <a href="https://en.wikipedia.org/wiki/George_Boole">George Boole</a></li>
 <li>JavaScript (a trademark of Oracle Corporation, it should always be written as trademarked)</li>
 <li>Python, TypeScript, Django, and other programming languages and framework names</li>
</ul>

<h3 id="Contractions">Contractions</h3>

<p>Our writing style tends to be casual, so you should feel free to use contractions (e.g., "don't", "can't", "shouldn't"), if you prefer.</p>

<h3 id="Pluralization">Pluralization</h3>

<p>Use English-style plurals, not the Latin- or Greek-influenced forms.</p>

<ul>
 <li><strong>Correct</strong>: syllabuses, octopuses</li>
 <li><strong>Incorrect</strong>: syllabi, octopi</li>
</ul>

<h3 id="Hyphenation">Hyphenation</h3>

<p>Hyphenate compounds when the last letter of the prefix is a vowel and is the same as the first letter of the root.</p>

<ul>
 <li><font color="green"><strong>Correct</strong></font>: email, re-elect, co-op</li>
 <li><font color="red"><strong>Incorrect</strong></font>: e-mail, reelect, coop</li>
</ul>

<h3 id="Gender-neutral_language">Gender-neutral language</h3>

<p>It is a good idea to use gender-neutral language in any writing where gender is irrelevant to the subject matter, to make the text as inclusive as possible. So, for example, if you are talking about the actions of a specific man, usage of "he"/"his" is fine; but if the subject is a person of either gender, "he"/"his" isn't appropriate.<br>
 <br>
 Let's take the following example:</p>

<blockquote>
<p>A confirmation dialog appears, asking the user if he allows the Web page to make use of his Web cam.</p>
</blockquote>

<blockquote>
<p>A confirmation dialog appears, asking the user if she allows the Web page to make use of her Web cam.</p>
</blockquote>

<p>Both versions are gender-specific. To fix this, use gender-neutral pronouns:</p>

<blockquote>
<p>A confirmation dialog appears, asking the user if they allow the Web page to make use of their Web cam.</p>
</blockquote>

<div class="blockIndicator note">
<p>MDN allows the use of this very common syntax (which is controversial among usage authorities) to make up for the lack of a neutral gender in English.</p>

<p>The use of the third-person plural as a gender neutral pronoun (that is, using "they," "them", "their," and "theirs") is an accepted practice, commonly known as "<a href="https://en.wikipedia.org/wiki/Singular_they">singular 'they.'</a>"</p>
</div>

<p>You can use both genders:</p>

<blockquote>
<p>A confirmation dialog appears, asking the user if he or she allows the web page to make use of his/her web cam.</p>
</blockquote>

<p>Making the users plural:</p>

<blockquote>
<p>A confirmation dialog appears, asking the users if they allow the web page to make use of their web cams.</p>
</blockquote>

<p>The best solution, of course, is to rewrite and eliminate the pronouns:</p>

<blockquote>
<p>A confirmation dialog appears, requesting the user's permission for web cam access.</p>
</blockquote>

<blockquote>
<p>A confirmation dialog box appears, which asks the user for permission to use the web cam.</p>
</blockquote>

<p>The last way of dealing with the problem is arguably better. It is not only grammatically more correct, but removes some of the complexity associated with dealing with genders across different languages that may have wildly different gender rules. This solution can make translation easier for both readers and localizers.</p>

<h3 id="Numbers_and_numerals">Numbers and numerals</h3>

<h4 id="Dates">Dates</h4>

<p>For dates (not including dates in code samples) use the format "January 1, 1990".</p>

<ul>
 <li><strong>Correct</strong>: February 24, 2006</li>
 <li><strong>Incorrect</strong>: February 24th, 2006; 24 February, 2006; 24/02/2006</li>
</ul>

<p>Alternately, you can use the YYYY/MM/DD format.</p>

<ul>
 <li><strong>Correct</strong>: 2006/02/24</li>
 <li><strong>Incorrect</strong>: 02/24/2006; 24/02/2006; 02/24/06</li>
</ul>

<h4 id="Decades">Decades</h4>

<p>For decades, use the format "1990s". Don't use an apostrophe.</p>

<ul>
 <li><strong>Correct</strong>: 1990s</li>
 <li><strong>Incorrect</strong>: 1990's</li>
</ul>

<h4 id="Plurals_of_numerals">Plurals of numerals</h4>

<p>For plurals of numerals add "s". Don't use an apostrophe.</p>

<ul>
 <li><strong>Correct</strong>: 486s</li>
 <li><strong>Incorrect</strong>: 486's</li>
</ul>

<h4 id="Commas">Commas</h4>

<p>In running text, use commas only in five-digit and larger numbers.</p>

<ul>
 <li><strong>Correct</strong>: 4000; 54,000</li>
 <li><strong>Incorrect</strong>: 4,000; 54000</li>
</ul>

<h3 id="Punctuation">Punctuation</h3>

<h4 id="Serial_comma">Serial comma</h4>

<p><strong>Use the serial comma</strong>. The serial (also known as "Oxford") comma is the comma that appears before the conjunction in a series of three or more items.</p>

<ul>
 <li><strong>Correct</strong>: I will travel on trains, planes, and automobiles.</li>
 <li><strong>Incorrect</strong>: I will travel on trains, planes and automobiles.</li>
</ul>

<div class="blockIndicator note">
<p>This is in contrast to the <a href="https://www.mozilla.org/en-US/styleguide/">One Mozilla style guide</a>, which specifies that the serial comma is not to be used. MDN is an exception to this rule.</p>
</div>

<h4 id="Apostrophes_and_quotation_marks">Apostrophes and quotation marks</h4>

<p><strong>Do not use "curly" quotes and quotation marks.</strong> On MDN, we only use straight quotes and apostrophes.</p>

<p>There are a couple of reasons for this.</p>

<ol>
 <li>We need to choose one or the other for consistency.</li>
 <li>If curly quotes or apostrophes make their way into code snippets—even inline ones—readers may copy and paste them, expecting them to function (which they will not).</li>
</ol>

<ul>
 <li><strong>Correct</strong>: Please don't use "curly quotes."</li>
 <li><strong>Incorrect</strong>: Please don’t use “curly quotes.”</li>
</ul>

<h3 id="Spelling">Spelling</h3>

<p>For words with variant spellings, always use their American English spelling.</p>

<p>In general, use the first entry at <a href="http://www.dictionary.com/">Dictionary.com</a>, unless that entry is listed as a variant spelling or as being primarily used in a non-American form of English. For example, if you <a href="http://www.dictionary.com/browse/behaviour">look up "behaviour"</a>, you find the phrase "Chiefly British" followed by a link to the American standard form, "<a href="http://dictionary.reference.com/browse/behavior">behavior</a>". Do not use variant spellings.</p>

<ul>
 <li><strong>Correct</strong>: localize, behavior</li>
 <li><strong>Incorrect</strong>: localise, behaviour</li>
</ul>

<h3 id="Terminology">Terminology</h3>

<h4 id="HTML_elements">HTML elements</h4>

<p>Use "elements" to refer to HTML and XML elements, rather than "tags". In addition, they should almost always be wrapped in "&lt;&gt;", and should be in the {{HTMLElement("code")}} style.</p>

<p>When you reference a given element for the first time in a section, you should use the <code>\{{HTMLElement}}</code> macro to create a link to the documentation for the element (unless you're writing within that element's reference document page).</p>

<ul>
 <li><strong>Correct</strong>: the {{HTMLElement("span")}} element</li>
 <li><strong>Incorrect</strong>: the span tag</li>
</ul>

<h4 id="Parameters_vs._arguments">Parameters vs. arguments</h4>

<p>The preferred term on MDN is <strong>parameters</strong>. Please avoid the term "arguments" for consistency whenever possible.</p>

<h4 id="User_interface_actions">User interface actions</h4>

<p>In task sequences, describe user interface actions using the imperative mood. Identify the user interface element by its label and type.</p>

<ul>
 <li><strong>Correct</strong>: Click the Edit button.</li>
 <li><strong>Incorrect</strong>: Click Edit.</li>
</ul>

<h3 id="Voice">Voice</h3>

<p>While the active voice is preferred, the passive voice is also acceptable, given the informal feel of our content. Try to be consistent, though.</p>

<h2 id="위키_마크업과_사용법">위키 마크업과 사용법</h2>

<h3 id="링크">링크</h3>

<p>링크는 위키를 강력한 배움과 가르침의 도구로 만드는 데 큰 역할을 합니다. 아래에서 관련한 기본적 정보를 찾을 수 있지만, 에디터 가이드에 있는 <a href="/ko/docs/MDN/Contribute/Editor/Links">MDN에서 링크를 생성하고 편집하기</a> 에서는 완전한 가이드를  볼 수 있습니다.</p>

<p>우리는 당신이 문서간에 적절한 링크를 생성하도록 권장합니다; 링크는 콘덴츠 검색 용이성및 네비게이션을 개선하는데 도움을 주고, 구글과 같은 검색 엔진이 더 나은 검색결과를 제공하도록  중요한 콘텍스트를 제공 합니다. 모든 페이지는 단어나 구문에서 관련된 주제의 다른 페이지로 연결되는 좋은 링크집합을 가져야 합니다. 링크는 용어를 정의하거나 어떤 주제에 대한 상세하고 심화된 문서를 제공하는데에 모두 사용될 뿐만 아니라,  관련된 예제나 보다 관심이 갈만한 정보도 제공할 수도 있습니다.</p>

<p>MDN내부의 문서(내부 링크)뿐만아니라 MDN 외부의 페이지(외부 링크)도 쉽게 링크를 걸 수 있습니다 .</p>

<p>링크를 만드는 두 가지 방법이 있습니다:</p>

<ul>
 <li>에디터 툴바내의 링크 버튼을 이용하거나 <kbd>Ctrl</kbd>+<kbd>K</kbd> (맥에서는 <kbd>Cmd</kbd>+<kbd>K</kbd>)를 눌러서 명시적으로 링크를 성성합니다.</li>
 <li>또는, MDN의 강력한 매크로 시스템을 이용하여 자동적으로 혹은 입력값 기반으로 링크를 생성할 수 있습니다.</li>
</ul>

<p>어떤 텍스트에 링크를 연결할 것인지에 대해, 몇가지 가이드라인을 소개합니다:</p>

<ul>
 <li><strong>필요한 링크를 생성할 매크로가 존재하는 모든 경우에, 매크로를 이용해도 됩니다. 꼭 이용해주세요.</strong> <a href="/ko/docs/MDN/Contribute/Editor/Links#Using_link_macros">링크 생성에 매크로 사용하기</a> 는 올바로 링크를 생성하도록 도울 뿐만 아니라, 미래에 MDN에 이루어질 개선이 당신의 링크에 자동적으로 적용되도록 합니다. .</li>
 <li><strong>API 이름에 대해서는, 문서에 쓰인 API 용어의 전체 문자열을 사용하세요.</strong> 가장 쉬운 방법은 당신에게 맞는 올바른 형식을 갖춘 링크를 구성하기에 <a href="/ko/docs/MDN/Contribute/Editor/Links#Linking_to_documentation_for_APIs">적절한 매크로를 사용하는 것</a> 이다.</li>
 <li>특정한 용어에 대해 논하거나 정의하는 페이지에 링크하기 위해, 링크 문자열에 용어의 이름만을 사용하세요; 그외의 추가적인 텍스트를 포함하지 마세요. 예를 들면:
  <ul>
   <li><strong>바름</strong>: You can use <a href="/ko/docs/Web/JavaScript">JavaScript</a> code to create dynamic applications on the Web.</li>
   <li><strong>틀림</strong>: You can use <a href="/ko/docs/Web/JavaScript">JavaScript code</a> to create dynamic applications on the Web.</li>
  </ul>
 </li>
 <li>반면에 , 약간 긴 문장에 유용한 링크를 추가할 때에는, 다음과 같이, 동작과 목적어만 포함하는 구문을 선택하도록 해보세요:
  <ul>
   <li><strong>바름</strong>: If you'd like to <a href="/ko/docs/Mozilla/Developer_guide">contribute to the Firefox project</a>, your first step is to <a href="/ko/docs/Mozilla/Developer_guide/Build_Instructions">download and build Firefox</a>.</li>
   <li><strong>틀림</strong>: <a href="/ko/docs/Mozilla/Developer_guide">If you'd like to contribute to the Firefox project</a>, your first step is to <a href="/ko/docs/Mozilla/Developer_guide/Build_Instructions">download and build</a> Firefox.</li>
  </ul>
 </li>
</ul>

<h4 id="URL_정책">URL 정책</h4>

<p>보안 때문에, 아래 스킴(schemes)을 사용한 링크만 생성할 수 있다:</p>

<ul>
 <li><code>http://</code></li>
 <li><code>https://</code></li>
 <li><code>ftp://</code></li>
 <li><code>mailto:</code></li>
</ul>

<p>이 외의 것은 동작할 수도 아닐수도 있지만, 편집 스태프에 의해 지원되거나 삭제되지 않을 것이다.</p>

<div class="blockIndicator note">
<p>특별히,  <code>about:</code> 이나 <code>chrome://</code> 스킴은 동작하지 않으므로 피해야 한다.</p>

<p>유사하게 , <code>javascript:</code> 스킴도 <code>jar:</code>와 마찬가지로 대부분의 모던 브라우저에서 막혀있다</p>
</div>

<h3 id="페이지_태그">페이지 태그</h3>

<p>Tags provide meta information about a page and/or indicate that a page has specific improvements needed to its content. Every page in the wiki should have tags.</p>

<p>You can find details on tagging in our <a href="/en-US/docs/MDN/Contribute/Howto/Tag">How to properly tag pages</a> guide.</p>

<p>The tagging interface lives at the bottom of a page while you're in edit mode, and looks something like this:</p>

<p><img alt="Screenshot of the UX for adding and removing tags on MDN" src="https://mdn.mozillademos.org/files/7859/tag-interface.png"></p>

<p>To add a tag, click in the edit box at the end of the tag list and type the tag name you wish to add. Tags will autocomplete as you type. Press <kbd>Enter</kbd> (or <kbd>Return</kbd>) to submit the new tag. Each article may have as many tags as needed. For example, an article about using JavaScript in AJAX programming might have both "JavaScript" and "AJAX" as tags.</p>

<p>To remove a tag, just click the little "<code>×</code>" icon in the tag.</p>

<h4 id="Tagging_pages_that_need_work">Tagging pages that need work</h4>

<p>In addition to using tags to track information about the documentation's quality and content, we also use them to mark articles as needing specific types of work.</p>

<h4 id="Tagging_obsolete_pages">Tagging obsolete pages</h4>

<p>Use the following tags for pages that are not current:</p>

<dl>
 <dt>Junk</dt>
 <dd>Use for spam, pages created by mistake, or content that is so bad that it should be deleted. Pages with this tag are deleted from time to time.</dd>
 <dt>Obsolete</dt>
 <dd>
 <p>Use for content that is technically superseded, but still valid in context. For example, this might be an HTML element that is obsolete in HTML5, but still valid in HTML 4.01.</p>

 </dd>
 <dt>Archive</dt>
 <dd>
 <p>Use for content that is technically superseded and no longer useful. If possible, add a note to the topic referring readers to a more current topic.</p>

 <p>For example, a page that describes how to use the Mozilla CVS repository should refer readers to a current topic on using Mercurial repos. (If no corresponding current topic exists, use the <em>NeedsUpdate</em> tag, and add an explanation on the Talk page.)</p>

 <p>Pages with the <em>Archive</em> tag are eventually moved from the main content of MDN to the <a href="/en-US/docs/Archive">Archive</a> section.</p>
 </dd>
</dl>

<h3 id="SEO_summary">SEO summary</h3>

<p>The SEO summary provides a short description of a page. It will be reported as a summary of the article to robots crawling the site, and will then appear in search results for the page. It is also used by macros that automate the construction of landing pages inside MDN itself. (In other words, it's not just for SEO.)</p>

<p>By default, the first paragraph of the page is used as the SEO summary. However, you can override this behavior by marking a section with the <a href="/en-US/docs/Project:MDN/Contributing/Editor_guide/Editing#Formatting_styles">"SEO summary" style in the WYSIWYG editor</a>.</p>

<h3 id="Landing_pages">Landing pages</h3>

<p><strong>Landing pages</strong> are pages at the root of a topic area of the site, such as the main <a href="/en-US/docs/CSS" title="CSS">CSS</a> or <a href="/en-US/docs/HTML" title="HTML">HTML</a> pages. They have a standard format that consists of three areas:</p>

<ol>
 <li>A brief (typically one paragraph) overview of what the technology is and how it's used. See <a href="#writing_a_landing_page_overview">Writing a landing page overview</a> for tips.</li>
 <li>A two-column list of links with appropriate headings. See <a href="#creating_a_page_link_list">Creating a page link list</a> for guidelines.</li>
 <li>An <strong>optional</strong> "Browser compatibility" section at the bottom of the page.</li>
</ol>

<h4 id="Creating_a_page_link_list">Creating a page link list</h4>

<p>The link list section of an MDN landing page consists of two columns. These are created using the following HTML:</p>

<pre class="notranslate">&lt;div class="row topicpage-table"&gt;
  &lt;div class="section"&gt;
    ... left column contents ...
  &lt;/div&gt;
  &lt;div class="section"&gt;
    ... right column contents ...
  &lt;/div&gt;
&lt;/div&gt;</pre>

<p>The left column should be a list of articles, with an <code>&lt;h2&gt;</code> header at the top of the left column explaining that it's a list of articles about the topic (e.g., "Documentation and tutorials about foo"); this header should use the CSS class "Documentation". Below that is a <code>&lt;dl&gt;</code> list of articles with each article's link in a <code>&lt;dt&gt;</code> block and a brief one-or-two sentence summary of the article in the corresponding <code>&lt;dd&gt;</code> block.</p>

<p>The right column should contain one or more of the following sections, in order:</p>

<dl>
 <dt>Getting help from the community</dt>
 <dd>This should provide information on Matrix chat rooms and mailing lists available on the topic. The heading should use the class "Community".</dd>
 <dt>Tools</dt>
 <dd>A list of tools the user can look at to help with the use of the technology described in this section of MDN. The heading should use the class "Tools".</dd>
 <dt>Related topics</dt>
 <dd>A list of links to landing pages for other, related, technologies of relevance. The heading should use the class "Related_Topics".</dd>
</dl>

<h2 id="Using_and_inserting_images">Using and inserting images</h2>

<p>It's sometimes helpful to provide an image in an article you create or modify, especially if the article is very technical.</p>

<p>To include an image:</p>

<ol>
 <li>Before uploading your image, please ensure that it's as small as possible by using an image optiization tool.
  <ul>
   <li>For bitmap images (JPG or PNG), consider a tool such as <a href="https://imageoptim.com/mac">ImageOptim</a> (macOS), <a href="https://tinypng.com/">TinyPNG</a> (web service), or <a href="https://trimage.org/">Trimage</a> (Linux).</li>
   <li>For SVG images, use the <code><a href="https://github.com/svg/svgo">svgo</a></code> tool to optimize the SVG file before sending it. The default configuration is fine.</li>
  </ul>
 </li>
 <li>Attach the desired image file to the article (at the bottom of every article in edit mode). If your artwork is a diagram in SVG format (which is ideal if there is text that may need to be localized), you can't upload it directly, but you can ask an MDN admin to do it for you.</li>
 <li>Click the "<strong>insert image</strong>" button in the MDN documentation WYSIWYG editor.</li>
 <li>In the WYSIWYG editor's drop-down list of attachments, select the newly created attachment that is your image.</li>
 <li>Press the <strong>OK</strong> button.</li>
</ol>

<div class="blockIndicator warning">
<p><strong>Important:</strong> Remember to save any changes you've made before uploading an attachment to your article! The editor is closed during the upload process, and currently <em>does not verify</em> whether or not you wish to save your work when it does so.</p>
</div>

<h2 id="Other_references">Other references</h2>

<h3 id="Preferred_style_guides">Preferred style guides</h3>

<p>If you have questions about usage and style not covered here, we recommend referring to the <a href="https://docs.microsoft.com/en-us/style-guide/welcome/">Microsoft Writing Style Guide</a>—or, failing that, the <a href="https://www.amazon.com/Chicago-Manual-Style-16th/dp/0226104206">Chicago Manual of Style</a>. An <a href="https://faculty.cascadia.edu/cma/HIST148/cmscrib.pdf">unofficial crib sheet for the Chicago Manual of Style</a> is available online.</p>

<h3 id="Preferred_dictionary">Preferred dictionary</h3>

<p>For questions of spelling, please refer to <a href="http://www.dictionary.com/">Dictionary.com</a>. The spelling checker for this site uses American English. Please do not use variant spellings (e.g., use <em>color</em> rather than <em>colour</em>).</p>

<p>We will be expanding the guide over time, so if you have specific questions that aren't covered in this document, please post them on the <a href="https://discourse.mozilla.org/c/mdn">MDN discussion forum</a>, so we know what should be added.</p>

<h3 id="MDN-specific">MDN-specific</h3>

<ul>
 <li><a href="/en-US/docs/MDN/Contribute/Structures/Macros/Commonly-used_macros" title="Project:en/Custom_Templates">Commonly-used macros</a> on MDN, with explanations</li>
</ul>

<h3 id="Language_grammar_spelling">Language, grammar, spelling</h3>

<p>If you're interested in improving your writing and editing skills, you may find the following resources to be helpful.</p>

<ul>
 <li><a href="http://www.amazon.com/Writing-Well-30th-Anniversary-Nonfiction/dp/0060891548">On Writing Well</a>, by William Zinsser (Amazon link)</li>
 <li><a href="http://www.amazon.com/Style-Basics-Clarity-Grace-4th/dp/0205830765/">Style: The Basics of Clarity and Grace</a>, by Joseph Williams and Gregory Colomb (Amazon link)</li>
 <li><a href="https://brians.wsu.edu/common-errors-in-english-usage/">Common Errors in English</a></li>
 <li><a href="http://www-personal.umich.edu/~jlawler/aue.html">English Grammar FAQ</a> (alt.usage.english)</li>
 <li><a href="http://www.angryflower.com/bobsqu.gif">Bob's quick guide to the apostrophe, you idiots</a> (funny)</li>
 <li><a href="http://www.amazon.com/Merriam-Websters-Concise-Dictionary-English-Usage/dp/B004L2KNI2">Merriam-Webster's Concise Dictionary of English Usage</a> (Amazon link): Scholarly but user-friendly, evidence-based advice; very good for non-native speakers, especially for preposition usage.</li>
 <li><a href="http://english.stackexchange.com/">English Language and Usage StackExchange</a>: Question and answer site for English language usage.</li>
</ul>