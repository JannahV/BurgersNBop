html:

Using the starter code to help me configure an organized website I searched for images that looked similar to the examples provide for the homework assignment. 
 <div class="hero"></div>
    <div class="content">
        <div class="search-engine-optimization">
            <img src="https://searchengineland.com/wp-content/seloads/2014/08/seo-idea-lightbulbs-ss-1920.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>
        <div id="online-reputation-management" class="online-reputation-management">
            <img src="https://cdn.searchenginejournal.com/wp-content/uploads/2021/10/the-basics-of-online-reputation-management-61693484e216b-sej.png" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </div>
        <div id="social-media-marketing" class="social-media-marketing">
            <img src="https://cdn.searchenginejournal.com/wp-content/uploads/2021/10/11-proven-tips-to-get-more-social-media-followers-1-61769bea5719c-sej-1520x800.png" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </div>
    </div>
    <div class="benefits">
        <div class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="https://cdn3.vectorstock.com/i/1000x1000/46/47/lead-generation-icon-simple-element-vector-27064647.jpg" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
        <div class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="https://cdn.imgbin.com/0/22/12/imgbin-cost-effectiveness-analysis-cost-analysis-computer-icons-management-others-kZ4zAE3x2dNuyFGqFXfeR1jPc.jpg" />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>
        <div class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="https://www.shutterstock.com/image-vector/money-setting-260nw-664291279.jpg"></img>
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </div>
    </div>
    
    
    style.css:
    
    I also used starter code to make sure that the pictures I used fit within the borders.
    
    I had difficulties with adding the business photo at the top of the webpage so I used .hero and made it a background image. 
    
    .hero {
  height: 800px;
  width: 100%;
  margin-bottom: 25px;
  background-image: url("https://media.istockphoto.com/photos/glad-to-work-with-you-picture-id951514270?b=1&k=20&m=951514270&s=612x612&w=0&h=yp3UNtxVwiJZV3EHQqqKaS3md7HtBkVwHvH5uhcfcPE=");
  background-size: cover;
  background-position: center;
}
