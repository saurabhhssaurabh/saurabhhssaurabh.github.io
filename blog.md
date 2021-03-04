---
layout: page
title: Blog
comments: false
---

<!-- Style for the blog page is borrowed from lena voita's page -->

<style>

  #thumbnail {
    box-shadow: 0 5px 10px rgba(0,0,0,0.19), 0 3px 3px rgba(0,0,0,0.23);
  }
  #thumbnail:hover {
    box-shadow: 0 12px 24px rgba(0,0,0,0.19), 0 8px 8px rgba(0,0,0,0.23);
  }

  .fullCard {
    width: 750px;
    border: 1px solid #ccc;
    border-radius: 5px;
    margin: 10px 5px;
    padding: 4px;

  }
  .cardContent {
    padding: 10px;

  }

  .center {
    display: block;
    margin-left: auto;
    margin-right: auto;
  }

</style>



<div class="fullCard" id="thumbnail" >
    <div class="cardContent">

        <h1 style="font-size:28px;">Source and Target Contributions to NMT Predictions</h1>

        <video width="300" height="auto" style="float: right; margin-left: 15px;" loop autoplay muted>
          <source src="../resources/posts/src_dst_nmt/src_dst_main.mp4" type="video/mp4">
        </video>

        <span style="font-size:14px;">
        This is a post for the paper
            <a href="https://arxiv.org/pdf/2010.10907.pdf">
                Analyzing the Source and Target Contributions to Predictions in Neural Machine Translation.
            </a>
        </span>


        <br/>
        <br/>
        <span style="font-size:15px;">
            In NMT, the generation of a target token is based on two types of context: the source and the prefix of the target sentence.
            We show how to evaluate the relative contributions of source and target to NMT predictions and find that:
        <ul>
          <li>models suffering from exposure bias are more prone to over-relying on target history (and hence to hallucinating) than
          the ones where the exposure bias is mitigated;</li>
          <li>models trained with more data rely on the source more and do it more confidently;</li>
          <li>the training process is non-monotonic with several distinct stages.</li>
        </ul>
        </span>

        <a class="pull-right" href="/posts/source_target_contributions_to_nmt.html" onMouseOver="document.readmore5.src='../resources/posts/buttons/button_read_more_push-min.png';" onMouseOut="document.readmore5.src='../resources/posts/buttons/button_read_more-min.png';">
        <img src="../resources/posts/buttons/button_read_more-min.png" name="readmore5" width=120px class="pull-right"></a>
        <a class="pull-right" href="https://arxiv.org/pdf/2010.10907.pdf" onMouseOver="document.readpaper5.src='../resources/posts/buttons/button_read_paper_push-min.png';" onMouseOut="document.readpaper5.src='../resources/posts/buttons/button_read_paper-min.png';">
        <img src="../resources/posts/buttons/button_read_paper-min.png" name="readpaper5" width=120px class="pull-right"></a>
        <a class="pull-right" href="https://github.com/lena-voita/the-story-of-heads" onMouseOver="document.viewcode5.src='../resources/posts/buttons/button_view_code_push-min.png';" onMouseOut="document.viewcode5.src='../resources/posts/buttons/button_view_code-min.png';">
        <img src="../resources/posts/buttons/button_view_code-min.png" name="viewcode5" width=120px></a>

        <span style="font-size:15px; text-align: right; float: right; color:gray">October 2020</span>

    </div>
</div>


<!-- ################################################################################### -->