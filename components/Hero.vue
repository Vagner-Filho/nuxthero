<template>
    <section class="hero mt-3">
        <h5>
            Mutual Funds
        </h5>
        <h1 class="mt-3">
            Secure Your <br> Kids Future
        </h1>
        <p class="mt-3 fund-description">
            Children’s fund is a form of mutual fund with specific child-related goals and terms. Commonly availed investments, solution-oriented plans for the rising cost of education.
        </p>
        <button class="button btn btn-know-more mt-3">
            Know More
        </button>
        <p class="round-checkbox mt-2">
            <input type="checkbox" name="" id="30d-free-trial" class="free-trial-check mt-2">
            <label for="30d-free-trial"></label>
            30 days free trial
        </p>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .hero { 
        color: white
    }
    .hero h1 {
        font: 600 4.0rem 'Roboto', sans-serif;
    }
    .hero .fund-description {
        font: 300 1.2rem 'Roboto', sans-serif;
    }
    .btn-know-more {
        background-color: #FF4BB5; color: white
    }
    .free-trial-check {
        color: white;
    }
    .round-checkbox{
        position: relative;
    }
    .round-checkbox label{
        background-color: white;
        border: 1px solid #ccc;
        border-radius: 50%;
        cursor: pointer;
        height: 18px;
        left: 0;
        position: absolute;
        top: 7px;
        width: 18px;
    }
    .round-checkbox label::after {
        border: 2px solid #fff;
        border-top: none;
        border-right: none;
        content: "";
        height: 8px;
        left: 2px;
        opacity: 0;
        position: absolute;
        top: 3px;
        transform: rotate(-45deg);
        width: 12px;
    }
    .round-checkbox input[type="checkbox"] {
        visibility: hidden;
        margin-right: 10px;
    }
    .round-checkbox input[type="checkbox"]:checked + label{
        background-color: #66bb6a;
        border-color: #66bb6a;
    }
    .round-checkbox input[type="checkbox"]:checked + label::after{
        opacity: 1;
    }

    @media(max-width: 991px) {
        .hero h1{
            font-size: 3.0rem;
        }
    }

</style>