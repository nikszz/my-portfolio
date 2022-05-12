<template>
  <div class="container">
    <div class="row">
      <div class="col-lg-6 mx-auto">
        <span class="ls bg-orange">Experience</span>
        <!-- Timeline -->
        <ul class="timeline">
          <li class="timeline-item bg-white rounded ml-3 p-4 shadow">
            <div class="timeline-arrow"></div>
            <h5 class="mb-0">Software Developer [Full-time]</h5>
            <p class="mb-0">Mobile Pogrammming India Pvt Ltd</p>
            <span class="small text-gray mb-0"
              ><i class="fa fa-clock-o mr-1"></i>Sep 2021 - Present</span
            >
            <!-- {{ calculateDuration(new Date(2021, 9)) }} -->
            <p class="text-small mt-2 font-weight-light">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
              scelerisque diam non nisi semper, et elementum lorem ornare.
              Maecenas placerat facilisis mollis. Duis sagittis ligula in
              sodales vehicula....
            </p>
          </li>
          <li class="timeline-item bg-white rounded ml-3 p-4 shadow">
            <div class="timeline-arrow"></div>
            <h5 class="mb-0">Software Engineer [Full-time]</h5>
            <p class="mb-0">Bluelupin Technologies Pvt. Ltd.</p>
            <span class="small text-gray mb-0"
              ><i class="fa fa-clock-o mr-1"></i>Mar 2020 - Sep 2021</span
            >
            <p class="text-small mt-2 font-weight-light">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
              scelerisque diam non nisi semper.
            </p>
            <p class="text-small mt-2 font-weight-light">
              Libero expedita explicabo eius fugiat quia aspernatur autem
              laudantium error architecto recusandae natus sapiente sit nam
              eaque, consectetur porro molestiae ipsam! Deleniti.
            </p>
          </li>
          <li class="timeline-item bg-white rounded ml-3 p-4 shadow">
            <div class="timeline-arrow"></div>
            <h5 class="mb-0">Web Developer Trainee [Internship]</h5>
            <p class="mb-0">Altercode IT Solutions</p>
            <span class="small text-gray mb-0"
              ><i class="fa fa-clock-o mr-1"></i>Aug 2019 - Oct 2019</span
            >
            <p class="text-small mt-2 font-weight-light">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
              scelerisque diam non nisi semper, et elementum lorem ornare.
              Maecenas placerat facilisis mollis. Duis sagittis ligula in
              sodales vehicula....
            </p>
          </li>
        </ul>
        <!-- End -->
      </div>
      <div class="col-lg-6 mx-auto">
        <span class="ls bg-orange">Education</span>
        <!-- Timeline -->
        <ul class="timeline">
          <li class="timeline-item bg-white rounded ml-3 p-4 shadow">
            <div class="timeline-arrow"></div>
            <h5 class="mb-0">Master of Computer Applications - MCA</h5>
            <p class="mb-0">Indira Gandhi National Open University</p>
            <span class="small text-gray mb-0"
              ><i class="fa fa-clock-o mr-1"></i>2017 - 2019 | Scored 62%</span
            >
            <p class="text-small mt-2 font-weight-light">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
              scelerisque diam non nisi semper, et elementum lorem ornare.
              Maecenas placerat facilisis mollis. Duis sagittis ligula in
              sodales vehicula....
            </p>
          </li>
          <li class="timeline-item bg-white rounded ml-3 p-4 shadow">
            <div class="timeline-arrow"></div>
            <h5 class="mb-0">Bachelor of Computer Applications - BCA</h5>
            <p class="mb-0">Indira Gandhi National Open University</p>
            <span class="small text-gray mb-0"
              ><i class="fa fa-clock-o mr-1"></i>2014 - 2017 | Scored 65%</span
            >
            <p class="text-small mt-2 font-weight-light">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
              scelerisque diam non nisi semper.
            </p>
            <p class="text-small mt-2 font-weight-light">
              Libero expedita explicabo eius fugiat quia aspernatur autem
              laudantium error architecto recusandae natus sapiente sit nam
              eaque, consectetur porro molestiae ipsam! Deleniti.
            </p>
          </li>
        </ul>
        <!-- End -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Time-line",
  methods: {
    calculateDuration(dateFrom) {
      let currentDate = new Date();
      return (
        currentDate.getMonth() -
        dateFrom.getMonth() +
        12 * (currentDate.getFullYear() - dateFrom.getFullYear())
      );
    },
  },
};
</script>
