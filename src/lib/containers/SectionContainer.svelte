<script>
    export let title;
    export let backgroundText;
</script>

<div class="container d-flex justify-content-between flex-column h-100">
    <div class="section-title flex-grow-1">
        <div class="row">
            <div class="col-lg-12">
                <div class="text-left">
                    <h2 data-aos="heading-show" class="text_background">
                        {title}
                        <span class="heading_background">{backgroundText}</span>
                    </h2>
                </div>
            </div>
        </div>
    </div>
    <div class="section-content flex-grow-1">
        <slot />
    </div>
</div>