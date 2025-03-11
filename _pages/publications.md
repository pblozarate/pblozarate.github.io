---
permalink: /research/
title: "Research"
author_profile: true

---
<!-- Add this to your research page or create a new page -->

<!-- CSS styles (add to your CSS file or place in <style> tags in your <head>) -->
<style>
  .research-section {
    max-width: 800px;
    margin: 2rem auto;
    font-family: 'Source Sans Pro', Helvetica, Arial, sans-serif;
  }
  
  .research-section h2 {
    font-size: 1.8rem;
    margin-bottom: 1.5rem;
    color: #333;
    border-bottom: 2px solid #f0f0f0;
    padding-bottom: 0.5rem;
  }
  
  .paper-item {
    margin-bottom: 1.5rem;
    padding-left: 1rem;
    border-left: 3px solid #3d6997;
  }
  
  .paper-header {
    cursor: pointer;
    padding: 0.5rem 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .paper-title {
    font-size: 1.2rem;
    font-weight: 600;
    color: #2c3e50;
    flex-grow: 1;
  }
  
  .paper-authors {
    font-style: italic;
    color: #555;
    margin-top: 0.3rem;
  }
  
  .expand-icon {
    margin-left: 10px;
    font-size: 1.1rem;
    color: #3d6997;
    transition: transform 0.3s ease;
  }
  
  .paper-content {
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.3s ease-out;
    padding-right: 1rem;
  }
  
  .paper-item.expanded .paper-content {
    max-height: 200px; /* Adjust as needed */
    margin-top: 0.7rem;
    margin-bottom: 0.7rem;
  }
  
  .paper-item.expanded .expand-icon {
    transform: rotate(90deg);
  }
  
  .paper-abstract {
    font-size: 0.95rem;
    color: #666;
    line-height: 1.5;
  }
  
  .tag {
    display: inline-block;
    font-size: 0.7rem;
    padding: 0.2rem 0.5rem;
    background-color: #f0f4f8;
    color: #3d6997;
    border-radius: 3px;
    margin-right: 0.5rem;
    margin-top: 0.5rem;
  }
</style>

<!-- HTML for Research Section -->
<section class="research-section">
  <h2>Work in Progress</h2>
  
  <div class="paper-item">
    <div class="paper-header" onclick="togglePaper(this.parentNode)">
      <div>
        <div class="paper-title">Importing Unions: German Migrants and the Rise of the American Labor Movement</div>
      </div>
      <span class="expand-icon">›</span>
    </div>
    <div class="paper-content">
      <div class="paper-tags">
        <span class="tag">Causal Inference</span>
        <span class="tag">Network Economics</span>
      </div>
      <div class="paper-abstract">Investigating novel methodological approaches to identifying causal relationships in markets with complex network structures.</div>
    </div>
  </div>
  
  <div class="paper-item">
    <div class="paper-header" onclick="togglePaper(this.parentNode)">
      <div>
        <div class="paper-title">Migration and Public Goods: Evidence from the Near-Universe of Italian Migrants</div>
        <div class="paper-authors">With <span class="coauthor">Giacomo Corneo</span>, <span class="coauthor">Chiara Malavasi</span> and <span class="coauthor">Guido Neidhöfer</span></div>
      </div>
      <span class="expand-icon">›</span>
    </div>
    <div class="paper-content">
      <div class="paper-tags">
        <span class="tag">Migration</span>
        <span class="tag">Public Goods</span>
      </div>
      <div class="paper-abstract">Examining how different climate policy instruments affect the rate and direction of technological innovation across sectors.</div>
    </div>
  </div>
  
  <div class="paper-item">
    <div class="paper-header" onclick="togglePaper(this.parentNode)">
      <div>
        <div class="paper-title">Evidence from Text-to-Image AI</div>
      </div>
      <span class="expand-icon">›</span>
    </div>
    <div class="paper-content">
      <div class="paper-abstract">Brief description of the ongoing research and its potential contributions to the field. Expected completion in Summer 2025.</div>
    </div>
  </div>
</section>

<!-- JavaScript for expand/collapse functionality -->
<script>
  function togglePaper(paperItem) {
    paperItem.classList.toggle('expanded');
  }
</script>
