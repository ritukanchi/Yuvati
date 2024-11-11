<script>
    // Any necessary script can go here
</script>

<style>
    .page {
        display: flex;
        justify-content: space-between;
        align-items: start;
        padding: 20px;
        gap: 2rem;
    }
    .divider {
        width: 1px;
        background-color: black;
        height: 300px;
    }
    .left, .right {
        width: 45%;
    }
    .head1, .head2 {
        font-size: 40px;
        font-weight: bold;
    }
    .subheadings {
        display: flex;
        gap: 20px;
        padding-top: 10px;
    }
    .lefttop, .righttop, .leftbottom, .rightbottom {
        font-size: 20px;
        font-weight: normal;
    }
    .horizontal-divider {
        border: none;
        border-top: 1px solid black;
        margin: 10px 0;
    }
    .body {
        font-size: 16px;
        padding-top: 20px;
    }
    a {
        text-decoration: none;
        color: black;
        font-weight: bold;
    }
    a:hover {
        color: pink; /* Optional: Add hover effect for links */
    }
</style>

<div class="page">
    <div class="left">
        <div class="head1">
            <p>What's buzzing!</p>
            <div class="subheadings">
                <div class="lefttop">
                    <a href="/Discover/tampons">Do not panic about tampons</a>
                </div>
                <div class="righttop">
                    <a href="/Discover/nutrition">Discover the latest in nutrition</a>
                </div>
            </div>

            <!-- Horizontal Divider -->
            <hr class="horizontal-divider" />

            <div class="subheadings">
                <div class="leftbottom">
                    <a href="/Discover/meftal-spas">Meftal Spas is totally safe</a>
                </div>
                <div class="rightbottom">
                    <a href="/Discover/fitness-trends">Get Moving with the Hottest Fitness Trends</a>
                </div>
            </div>
        </div>
    </div>

    <!-- Vertical Divider -->
    <div class="divider"></div>

    <div class="right">
        <div class="head2">
            <p>Expert Q&A</p>
        </div>
        <div class="body">
            <p>Ask the community: Weekly or monthly Q&A with gynecologists, dietitians, mental health professionals, and fitness trainers. Real Women, Real Stories: Interviews or stories of women sharing their health journeys, successes, and struggles.</p>
        </div>
    </div>
</div>
