<script>
export default{
    data(){
        return {
            count: 4
        }
    }
}
</script>

<template>
    <div id="notebook-paper">
        <header>
            <h1>Fancy Title</h1>
        </header>
        <div id="content">
            <div class="question">
                <span style="color:;font-weight: 600;">Why is AWS more economical than traditional data centers for applications with varying compute workloads? </span>
                <div class="options pl-3">
                    <div>
                        <input class="mx-1" type="radio" name="flexRadioDefault" id="${option}">
                        <label class="" for="${option}">Amazon EC2 costs are billed on a monthly basis</label>
                    </div>
                    <div>
                        <input class="mx-1" type="radio" name="flexRadioDefault" id="${option}">
                        <label class="" for="${option}">Users retain full administrative access to their Amazon EC2 instances.</label>
                    </div>
                    <div>
                        <input class="mx-1" type="radio" name="flexRadioDefault" id="${option}">
                        <label class="" for="${option}">Amazon EC2 instances can be launched on demand when needed.</label>
                    </div>
                    <div>
                        <input class="mx-1" type="radio" name="flexRadioDefault" id="${option}">
                        <label class="" for="${option}">Users can permanently run enough instances to handle peak workloads</label>
                    </div>
                </div>
            </div><br>
            <div class="question">
                <span style="color:;font-weight: 600;">Which AWS service would simplify the migration of a database to AWS? </span>
                <div class="options pl-3">
                    <div>
                        <input class="mx-1" type="radio" name="flexRadioDefault1" id="${option}">
                        <label class="" for="${option}">AWS Storage Gateway</label>
                    </div>
                    <div>
                        <input class="mx-1" type="radio" name="flexRadioDefault1" id="${option}">
                        <label class="" for="${option}">AWS Database Migration Service (AWS DMS).</label>
                    </div>
                    <div>
                        <input class="mx-1" type="radio" name="flexRadioDefault1" id="${option}">
                        <label class="" for="${option}">Amazon EC2</label>
                    </div>
                    <div>
                        <input class="mx-1" type="radio" name="flexRadioDefault1" id="${option}">
                        <label class="" for="${option}">Amazon AppStream 2.0</label>
                    </div>
                </div>
            </div><br>
        </div>
    </div>
</template>