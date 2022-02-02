<script>
    // TODO: create comments component
    import Comments from './Comments.svelte'
</script>

<div class="Card">
    <div class="Card-container">
        <div class="Card-header">
            <div class="Card-user">
                <img src="https://randomuser.me/api/portraits/men/30.jpg" alt="">
                <h2>
                    Random.user
                    <span>Jalisco, MX</span>
                </h2>
            </div>
            <div class="Card-settings">
                <i class='fas fa-ellipsis-h' />
            </div>
        </div>
        <div class="Car-photo">
            <figure>
                <img src="https://randomuser.me/api/portraits/men/30.jpg" alt="">
            </figure>
        </div>
        <div class="Card-icons">
            <div class="Card-icons-firsts">
                <i class="fas fa-heart"/>
                <i class="fas fa-paper-plane"/>
            </div>
            <div class="Card-icons-seconds">
                <i class="fa fas-bookmark"/>
            </div>
        </div>
        <div class="Card-description">
            <h3>Random.user</h3>
            <p>Hello</p>
        </div>
        <Comments />
    </div>
</div>