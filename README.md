# collapsible-content
Adding collapsible content to your website provides a more interactive user experience (UX) while also allowing you to add more content to your website. [Solodev](https://www.solodev.com/) will show you how to easily add a styled and collapsible FAQ section to your website.

## Tutorial

For detailed instructions, view Solodev's [Adding Collapsible Content to your Website with Boostrap](https://www.solodev.com/blog/web-design/adding-collapsible-content-to-your-website-with-bootstrap.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/27v532td/).

## HTML

The FAQ has basic HTML for displaying questions and answers.

```
<div class="faqs-items">
<div class="container small-container">
<div id="faq">
   <section class="accordion-section">
      <section class="row">
         <div class="col-md-4 accordion-item">
            <h3 class="accordion-section-header">Support</h3>
            <div aria-multiselectable="true" class="panel-group" role="tablist">
               <div class="panel section">
                  <div class="panel-heading row" id="header-panel14343" role="tab">
                     <div class="col-sm-12">
                        <h4 class="panel-title"><a aria-controls="collapse-panel14343" class="faq-toggle collapsed" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14343" role="button"><i class="fa fa-angle-down caret-faq">&nbsp;</i></a><a aria-controls="collapse-panel14343" class="collapsed" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14343" role="button">What are the benefits of WebCorpCo?</a></h4>
                     </div>
                  </div>
                  <div aria-labelledby="header-panel14343" class="panel-collapse collapse" id="collapse-panel14343" role="tabpanel" aria-expanded="false" style="height: 0px;">
                     <div class="panel-body">
                        <p></p>
                        <p>With WebCorpCo, you and your visitors will benefit from a finely-tuned technology stack that drives the highest levels of site performance, speed and engagement - and contributes more to your bottom line.</p>
                    
                        <p></p>
                     </div>
                  </div>
               </div>
            </div>
            <div aria-multiselectable="true" class="panel-group" role="tablist">
               <div class="panel section">
                  <div class="panel-heading row" id="header-panel14303" role="tab">
                     <div class="col-sm-12">
                        <h4 class="panel-title"><a aria-controls="collapse-panel14303" class="collapsed faq-toggle" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14303" role="button"><i class="fa fa-angle-down caret-faq">&nbsp;</i></a><a aria-controls="collapse-panel14303" class="collapsed" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14303" role="button">Where can I go to get support?</a></h4>
                     </div>
                  </div>
                  <div aria-labelledby="header-panel14303" class="panel-collapse collapse" id="collapse-panel14303" role="tabpanel">
                     <div class="panel-body sumome-article" style="position: relative;">
                        <p></p>
                        <p>Head on over to <a href="//solodev.zendesk.com/hc/en-us">support.webcorpco.com</a> for all of your support needs.</p>
                     </div>
                  </div>
               </div>
            </div>
            <div aria-multiselectable="true" class="panel-group" role="tablist">
               <div class="panel section">
                  <div class="panel-heading row" id="header-panel14342" role="tab">
                     <div class="col-sm-12">
                        <h4 class="panel-title"><a aria-controls="collapse-panel14342" class="collapsed faq-toggle" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14342" role="button"><i class="fa fa-angle-down caret-faq">&nbsp;</i></a><a aria-controls="collapse-panel14342" class="collapsed" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14342" role="button">How easy is WebCorpCo?</a></h4>
                     </div>
                  </div>
                  <div aria-labelledby="header-panel14342" class="panel-collapse collapse" id="collapse-panel14342" role="tabpanel">
                     <div class="panel-body">
                        <p>Building a website is extremely easy. With a working knowledge of HTML and CSS you will be able to have a site up and running in no time.</p>
                     </div>
                  </div>
               </div>
            </div>
            <div aria-multiselectable="true" class="panel-group" role="tablist">
               <div class="panel section">
                  <div class="panel-heading row" id="header-panel14314" role="tab">
                     <div class="col-sm-12">
                        <h4 class="panel-title"><a aria-controls="collapse-panel14314" class="collapsed faq-toggle" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14314" role="button"><i class="fa fa-angle-down caret-faq">&nbsp;</i></a><a aria-controls="collapse-panel14314" class="collapsed" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14314" role="button">Does WebCorpCo offer any training?</a></h4>
                     </div>
                  </div>
                  <div aria-labelledby="header-panel14314" class="panel-collapse collapse" id="collapse-panel14314" role="tabpanel">
                     <div class="panel-body">
                        <p>Yes, we have how to guides in our Support section and we also offer personal training via our support plan. If you are interested in 1 on 1 training options, just fill out our contact form and we will be glad to speak with you.</p>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="col-md-4 accordion-item">
            <h3 class="accordion-section-header">Billing</h3>
            <div aria-multiselectable="true" class="panel-group" role="tablist">
               <div class="panel section">
                  <div class="panel-heading row" id="header-panel14327" role="tab">
                     <div class="col-sm-12">
                        <h4 class="panel-title"><a aria-controls="collapse-panel14327" class="collapsed faq-toggle" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14327" role="button"><i class="fa fa-angle-down caret-faq">&nbsp;</i></a><a aria-controls="collapse-panel14327" class="collapsed" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14327" role="button">How much does WebCorpCo cost?</a></h4>
                     </div>
                  </div>
                  <div aria-labelledby="header-panel14327" class="panel-collapse collapse" id="collapse-panel14327" role="tabpanel">
                     <div class="panel-body">
                        <p>Pricing for WebCorpCo is based on your needs please check out <a href="/pricing/">https://www.webcorpco.com/pricing</a> to find out how much it would cost.</p>
                     </div>
                  </div>
               </div>
            </div>
            <div aria-multiselectable="true" class="panel-group" role="tablist">
               <div class="panel section">
                  <div class="panel-heading row" id="header-panel14328" role="tab">
                     <div class="col-sm-12">
                        <h4 class="panel-title"><a aria-controls="collapse-panel14328" class="collapsed faq-toggle" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14328" role="button"><i class="fa fa-angle-down caret-faq">&nbsp;</i></a><a aria-controls="collapse-panel14328" class="collapsed" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14328" role="button">How do I edit my billing information?</a></h4>
                     </div>
                  </div>
                  <div aria-labelledby="header-panel14328" class="panel-collapse collapse" id="collapse-panel14328" role="tabpanel">
                     <div class="panel-body">
                        <p>In order to edit your billing information you will have to login to your account at <a href="/login.stml">https://www.webcorpco.com/login.stml</a> and go to “Billing Information” from there you can edit your billing information.</p>
                     </div>
                  </div>
               </div>
            </div>
            <div aria-multiselectable="true" class="panel-group" role="tablist">
               <div class="panel section">
                  <div class="panel-heading row" id="header-panel14330" role="tab">
                     <div class="col-sm-12">
                        <h4 class="panel-title"><a aria-controls="collapse-panel14330" class="collapsed faq-toggle" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14330" role="button"><i class="fa fa-angle-down caret-faq">&nbsp;</i></a><a aria-controls="collapse-panel14330" class="collapsed" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14330" role="button">Can I do annual billing?</a></h4>
                     </div>
                  </div>
                  <div aria-labelledby="header-panel14330" class="panel-collapse collapse" id="collapse-panel14330" role="tabpanel">
                     <div class="panel-body">
                        <p>Yes, annual billing is available.</p>
                     </div>
                  </div>
               </div>
            </div>
            <div aria-multiselectable="true" class="panel-group" role="tablist">
               <div class="panel section">
                  <div class="panel-heading row" id="header-panel14301" role="tab">
                     <div class="col-sm-12">
                        <h4 class="panel-title"><a aria-controls="collapse-panel14301" class="collapsed faq-toggle" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14301" role="button"><i class="fa fa-angle-down caret-faq">&nbsp;</i></a><a aria-controls="collapse-panel14301" class="collapsed" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14301" role="button">Will my data be private and secure?</a></h4>
                     </div>
                  </div>
                  <div aria-labelledby="header-panel14301" class="panel-collapse collapse" id="collapse-panel14301" role="tabpanel">
                     <div class="panel-body">
                        <p>Yes, security is integral to the WebCorpCo Platform and is embedded into every architectural layer.</p>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="col-md-4 accordion-item">
            <h3 class="accordion-section-header">Infrastructure</h3>
            <div aria-multiselectable="true" class="panel-group" role="tablist">
               <div class="panel section">
                  <div class="panel-heading row" id="header-panel14341" role="tab">
                     <div class="col-sm-12">
                        <h4 class="panel-title"><a aria-controls="collapse-panel14341" class="collapsed faq-toggle" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14341" role="button"><i class="fa fa-angle-down caret-faq">&nbsp;</i></a><a aria-controls="collapse-panel14341" class="collapsed" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14341" role="button">What is the uptime for WebCorpCo?</a></h4>
                     </div>
                  </div>
                  <div aria-labelledby="header-panel14341" class="panel-collapse collapse" id="collapse-panel14341" role="tabpanel">
                     <div class="panel-body">
                        <p>Using Amazon AWS technology which is an industry leader for reliability you will be able to experience an uptime in the vicinity of 99.95%</p>
                     </div>
                  </div>
               </div>
            </div>
            <div aria-multiselectable="true" class="panel-group" role="tablist">
               <div class="panel section">
                  <div class="panel-heading row" id="header-panel14305" role="tab">
                     <div class="col-sm-12">
                        <h4 class="panel-title"><a aria-controls="collapse-panel14305" class="collapsed faq-toggle" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14305" role="button"><i class="fa fa-angle-down caret-faq">&nbsp;</i></a><a aria-controls="collapse-panel14305" class="collapsed" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14305" role="button">What technology do we use?</a></h4>
                     </div>
                  </div>
                  <div aria-labelledby="header-panel14305" class="panel-collapse collapse" id="collapse-panel14305" role="tabpanel">
                     <div class="panel-body">
                        <p>WebCorpCo is built using PHP, Javascript, HTML and CSS</p>
                     </div>
                  </div>
               </div>
            </div>
            <div aria-multiselectable="true" class="panel-group" role="tablist">
               <div class="panel section">
                  <div class="panel-heading row" id="header-panel14319" role="tab">
                     <div class="col-sm-12">
                        <h4 class="panel-title"><a aria-controls="collapse-panel14319" class="collapsed faq-toggle" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14319" role="button"><i class="fa fa-angle-down caret-faq">&nbsp;</i></a><a aria-controls="collapse-panel14319" class="collapsed" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14319" role="button">What browsers do we support?</a></h4>
                     </div>
                  </div>
                  <div aria-labelledby="header-panel14319" class="panel-collapse collapse" id="collapse-panel14319" role="tabpanel">
                     <div class="panel-body">
                        <p>We support the current and previous major releases of Google Chrome™, Firefox®, Safari®, Microsoft® Edge™, and Internet Explorer® on a rolling basis. Each time a new version is released, we begin supporting that version and stop supporting the third most recent version</p>
                     </div>
                  </div>
               </div>
            </div>
            <div aria-multiselectable="true" class="panel-group" role="tablist">
               <div class="panel section">
                  <div class="panel-heading row" id="header-panel14307" role="tab">
                     <div class="col-sm-12">
                        <h4 class="panel-title"><a aria-controls="collapse-panel14307" class="collapsed faq-toggle" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14307" role="button"><i class="fa fa-angle-down caret-faq">&nbsp;</i></a><a aria-controls="collapse-panel14307" class="collapsed" data-toggle="collapse" aria-expanded="false" data-parent="#accordion1" href="#collapse-panel14307" role="button">Will WebCorpCo scale with my website?</a></h4>
                     </div>
                  </div>
                  <div aria-labelledby="header-panel14307" class="panel-collapse collapse" id="collapse-panel14307" role="tabpanel">
                     <div class="panel-body">
                        <p>Yes, since WebCorpCo is entirely cloud based, new servers can easily be added or upgraded to increased memory to handle your growing company’s digital demands.</p>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </section>
   </section>
</div>
```
## CSS

All necessary CSS is in faq.css

## External Includes
```
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css">
<link rel="stylesheet" href="faq.css">
```
