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
        height:300px; /* Adjust as per content */
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
    .body {
        font-size: 16px;
        padding-top: 20px;
    }
</style>

<div class="page">
    <div class="left">
        <div class="head1">
            <p>What's buzzing!</p>
            <div class="subheadings">
                <div class="lefttop">
                    <p>Do not panic about tampons</p>
                </div>
                <div class="righttop">
                    <p>Discover the latest in nutrition</p>
                </div>
            </div>
            <div class="subheadings">
                <div class="leftbottom">
                    <p>Meftal Spas is totally safe</p>
                </div>
                <div class="rightbottom">
                    <p>Get Moving with the Hottest Fitness Trends</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Divider -->
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
