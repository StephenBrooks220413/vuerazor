<template>
    <div class="contact">
        <br /><br />
        <h1>Contact Us</h1>
        <div class="container">
            <h5>
                1151 Main St. - Chicago, IL. <br />
                P: 555-555-5555 / F: 555-551-1110
            </h5>
        </div>
        <br /><br />
        <div class="container text-center">
            <form class="max">
                <!-- Name input -->
                <div class="form-outline mb-4">
                    <input type="text" id="form4Example1" class="form-control" />
                    <label class="form-label" for="form4Example1">Name</label>
                </div>

                <!-- Email input -->
                <div class="form-outline mb-4">
                    <input type="email" id="form4Example2" class="form-control" />
                    <label class="form-label" for="form4Example2">Email address</label>
                </div>

                <!-- Message input -->
                <div class="form-outline mb-4">
                    <textarea class="form-control" id="form4Example3" rows="4"></textarea>
                    <label class="form-label" for="form4Example3">Message</label>
                </div>

                <!-- Checkbox -->
                <div class="form-check d-flex justify-content-center mb-4">
                    <input class="form-check-input me-2"
                           type="checkbox"
                           value=""
                           id="form4Example4"
                           checked />
                    <label class="form-check-label" for="form4Example4">
                        Send me a copy of this message
                    </label>
                </div>

                <!-- Submit button -->
                <button type="submit" class="btn btn-primary btn-block mb-4">Send</button>
            </form>
        </div>
        <br /><br />
    </div>
</template>

<script></script>

<style scoped>
    .max {
        max-width: 750px !important;
        height: auto;
        margin-left: auto;
        margin-right: auto;
    }

        .max input {
            background-color: lightgrey;
        }

        .max textarea {
            background-color: lightgrey;
        }
</style>