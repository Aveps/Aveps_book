<style>
.tooltiplink {
    position: relative;
}

.tooltiplink:hover::after {
    content: attr(data-title);
    background-color: #8fbc8f;
    color: #fff;
    padding: 8px;
    border-radius: 4px;
    font-size: 12px;
    line-height: 14px;
    display: block;
    position: absolute;
    top: 100%;
    left: 50%;
    transform: translateX(-50%);
    white-space: nowrap;
    z-index: 1;
}
  
</style>

<h1>Привет Aveps!!!</h1>
<strong>(C) 2025 Aveps</strong>
<p>Проба отображения GitHub Pages</p>

<a class="tooltiplink" href="https://stm66.github.io/" data-title="Михаил stm66">Сайт о LINUX</a>
