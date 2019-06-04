<template>
  <div id="mirantis">
    <!-- Main Section -->
    <section class="main-section align-middle d-flex align-items-center justify-content-center">
      <div class="container">
        <div class="row">
          <div class="col-12 text-center">
            <h1 class="_h1">
              Ceph in Mirantis Cloud Platform
            </h1>
            <p>
              Best-in-class options to deliver software-defined storage (SDS), including Ceph, <br/>into cloud infrastructures
            </p>
          </div>
          <div class="col-12 col-md-6 text-center text-md-right mt-4">
            <button type="button" class="btn btn-outline-primary sign-up-btn">
              SIGN UP FOR LIVE DEMO
            </button>
          </div>
          <div class="col-12 col-md-6 text-center text-md-left mt-4">
            <button type="button" class="btn btn-outline-primary view-deployment-btn">
              VIEW DEPLOYMENT GUIDE
            </button>
          </div>
        </div>
      </div>
    </section>
    <!-- Pure-Play Section -->
    <section class="pure-ceph align-middle d-flex align-items-center justify-content-center">
      <div class="container">
        <div class="row">
          <div class="col-lg-6 text-center text-lg-left order-1">
            <h2 class="_h2">
              Pure-Play Open Cloud Storage
            </h2>
            <p>
              Cloud native workloads are largely stateless, but ultimately all of that activity is stored somewhere. As your developers deploy workloads to your on-prem cloud, they need the ability to provision both block and object storage for themselves. MCP leverages Ceph, the most popular and widely adopted block storage choice for private clouds. Applications, virtual machines, containers and image repositories can utilize Ceph for different types of storage, including ephemeral block storage, persistent block and object storage. For cloud native applications, where existing SAN and NAS storage solutions do not scale, is a perfect choice.
            </p>
          </div>
          <div class="col-lg-6 text-left text-lg-right order-2 mt-4">
            <img src="../assets/cinder-diagram@2x.png" alt="" class="img-fluid">
          </div>
        </div>
      </div>
    </section>
    <!-- Why Ceph Section -->
    <section class="why-ceph align-middle d-flex align-items-center justify-content-center">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-9 text-center">
            <img src="../assets/ceph-logo@2x.png" width="90" alt="" class="img-fluid">
            <h2 class="_h2 mt-3 mb-4">
              Why Ceph?
            </h2>
            <p>
              While your developers need a cloud storage solution, IT/OPS needs a unified pool of storage that can be scaled up by simply adding storage server nodes. Ceph is a “unified, distributed storage system designed for excellent performance, reliability and scalability.” (source: ceph.com). It is an open source software project to build scale-out storage that meets all of the above requirements for both block and object storage for OpenStack. Ceph has built-in self-healing and can withstand underlying hardware failures; additional capacity can be added whenever required.
            </p>
          </div>
        </div>
        <div class="row ceph-1">
          <div class="col-1 d-none d-lg-inline-block">
            <img width="65" src="../assets/ic-sm-scaling.svg" alt="" class="img-fluid">
          </div>
          <div class="col-sm-6 col-lg-5 text-center text-lg-left mt-5 mt-sm-0">
            <h2 class="_h2 mt-lg-2">
              Scale-Out Storage
            </h2>
            <div class="d-inline-block d-lg-none">
              <img width="65" src="../assets/ic-sm-scaling.svg" alt="" class="img-fluid mt-3 mb-3">
            </div>
            <p>
              Scale-up storage no longer works, clouds require storage to scale-out by simply adding nodes.
            </p>
          </div>
          <div class="col-1 d-none d-lg-inline-block">
            <img width="65" src="../assets/ic-sm-resilience.svg" alt="" class="img-fluid">
          </div>
          <div class="col-sm-6 col-lg-5 text-center text-lg-left mt-5 mt-sm-0">
            <h2 class="_h2 mt-lg-2">
              Self-Healing & Resilience in Software
            </h2>
            <div class="d-inline-block d-lg-none">
              <img width="65" src="../assets/ic-sm-resilience.svg" alt="" class="img-fluid mt-3 mb-3">
            </div>
            <p>
              Resilience in a cloud gets moved to the software layer as opposed to a hardware layer.
            </p>
          </div>
        </div>
        <div class="row mt-lg-5 ceph-1">
          <div class="col-1 d-none d-lg-inline-block">
            <img width="65" src="../assets/ic-sm-automation.svg" alt="" class="img-fluid">
          </div>
          <div class="col-sm-6 col-lg-5 text-center text-lg-left mt-5 mt-sm-0">
            <h2 class="_h2 mt-lg-2">
              Automated
            </h2>
            <div class="d-inline-block d-lg-none">
              <img width="65" src="../assets/ic-sm-automation.svg" alt="" class="img-fluid mt-3 mb-3">
            </div>
            <p>
              Storage in a cloud environment needs to be automated both for IT/OPS and for developers.
            </p>
          </div>
          <div class="col-1 d-none d-lg-inline-block">
            <img width="65" src="../assets/ic-sm-opensource.svg" alt="" class="img-fluid">
          </div>
          <div class="col-sm-6 col-lg-5 text-center text-lg-left mt-5 mt-sm-0">
            <h2 class="_h2 mt-lg-2">
              Open Source
            </h2>
            <div class="d-inline-block d-lg-none">
              <img width="65" src="../assets/ic-sm-opensource.svg" alt="" class="img-fluid mt-3 mb-3">
            </div>
            <p>
              Open source is a must in cloud environments. <br>Open source ensures velocity, access to continuous innovation and no lock-in.
            </p>
          </div>
        </div>     
      </div>
    </section>
    <!-- Ceph in MCP Section -->
    <section class="pure-ceph align-middle d-flex align-items-center justify-content-center">
      <div class="container">
        <div class="row">
          <div class="col-lg-6 text-center text-lg-left order-1">
            <h2 class="_h2">
              Ceph in MCP
            </h2>
            <p>
              We take open source Ceph and provide four key value-adds. First, Mirantis hardens Ceph by providing comprehensive in-house testing. Second, we include our deployment and lifecycle management toolchain DriveTrain. Third, we integrate Ceph with our monitoring solution StackLight. Finally, we provide a support subscription that includes a choice of service level agreements (SLAs), updates and upgrades, including a fully managed operations option called OpsCare.
            </p>
            <p>
              The Mirantis distribution of Ceph supports petabyte-scale, multiple interfaces (S3, Swift, block), and features such as access control, storage policies, snapshots, thin provisioning, caching, flash journals, storage pooling,
            </p>
          </div>
          <div class="col-lg-6 text-left text-lg-right order-2 mt-4">
            <img src="../assets/ceph-in-mcp-diagram@2x.png" alt="" class="img-fluid">
          </div>
        </div>
      </div>
    </section>
    <!-- Ceph Lifecycle -->
    <section class="ceph-lifecycle align-middle d-flex align-items-center justify-content-center">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-9 text-center">
            <h1 class="_h1">
              Ceph Lifecycle Management Using Mirantis DriveTrain and StackLight OSS
            </h1>
          </div>
        </div>
        <div class="row ceph-1">
          <div class="col-1 d-none d-lg-inline-block">
            <img width="65" src="../assets/ic-sm-drivetrain-vivid2.svg" alt="" class="img-fluid">
          </div>
          <div class="col-sm-6 col-lg-5 text-center text-lg-left mt-5 mt-sm-0">
            <h2 class="mb-4 _h2">
              DriveTrain
            </h2>
            <div class="d-inline-block d-lg-none mt-3 mb-3">
              <img width="65" src="../assets/ic-sm-drivetrain-vivid2.svg" alt="" class="img-fluid">
            </div>
            <p>
              Mirantis DriveTrain leverages Salt and Reclass automation to deploy and manage ongoing lifecycle operations of the entire cloud, including Ceph storage clusters. DriveTrain’s model-driven architecture includes formulas to implement and scale fully integrated Ceph clusters and the desired interfaces within the MCP open cloud. Take advantage of the CI/CD benefits brought by DriveTrain to enable the resilience and stability of Ceph to your cloud workloads allowing you to deliver and grow best-in-class software-defined storage services to customers.
            </p>
          </div>
          <div class="col-1 d-none d-lg-inline-block">
            <img width="65" src="../assets/ic-sm-stacklight-vivid2.svg" alt="" class="img-fluid">
          </div>
          <div class="col-sm-6 col-lg-5 text-center text-lg-left mt-5 mt-sm-0">
            <h2 class="mb-4 _h2">
              StackLight
            </h2>
            <div class="d-inline-block d-lg-none mt-3 mb-3">
              <img width="65" src="../assets/ic-sm-stacklight-vivid2.svg" alt="" class="img-fluid">
            </div>
            <p>
              Keep tabs on the performance and utilization of the Ceph storage across your workloads from within Mirantis StackLight OSS. The DevOps Portal within StackLight provides real-time data metrics regarding how your users are employing the Ceph clusters. As an early detection and comprehensive alerting operations support system, StackLight enables IT operators to closely monitor and deliver high availability of Ceph services to customers.
            </p>
          </div>
        </div>   
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Mirantis'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css?family=Montserrat&display=swap');

  .main-section {
    background-image: url('../assets/birds-hero-bg@2x.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    color: #fff;
    height: 100%;
    width: 100%;
    min-height: 667px;
    position: relative;
  }

  .main-section p {
    margin-top: 40px;
  }

  ._h1 {
    font-weight: bold;
  }
  ._h2 {
    font-weight: bold;
  }

  .sign-up-btn {
    color: #fff;
    font-weight: bold;
    font-size: smaller;
    background-color: #ef2369;
    border-color: #ef2369;
    border-radius: 0px;
  }

  .sign-up-btn:hover {
    background-color: #ef2369;
    border-color: #ef2369;
    opacity: .8;
    -webkit-box-shadow: 9px 6px 35px 3px rgba(239,35,105,0.71);
    -moz-box-shadow: 9px 6px 35px 3px rgba(239,35,105,0.71);
    box-shadow: 9px 6px 35px 3px rgba(239,35,105,0.71);
  }

  .sign-up-btn:active {
    background-color: transparent!important;
    border-color: #fff!important;
  }

  .sign-up-btn:focus {
    box-shadow: none!important;
  }

  .view-deployment-btn {
    color: #fff;
    border-color: #fff;
    border-radius: 0px;
    font-weight: bold;
    font-size: smaller;
  }

  .view-deployment-btn:focus {
    box-shadow: none!important;
  }

  .view-deployment-btn:active {
    background-color: transparent!important;
    border-color: #fff!important;
  }

  .view-deployment-btn:hover {
    opacity: 0.8;
    background-color: transparent;
    border-color: #fff;
    -webkit-box-shadow: 9px 6px 20px 1px rgba(255,255,255,1);
    -moz-box-shadow: 9px 6px 20px 1px rgba(255,255,255,1);
    box-shadow: 9px 6px 20px 1px rgba(255,255,255,1);
  }

  .pure-ceph {
    background-color: #e6efed;
  }

  .pure-ceph .row {
    padding-top: 72px;
    padding-bottom: 78px;
  }
  .pure-ceph p {
    margin-top: 1.5rem;
    font-size: 1.125rem;
    line-height: 1.7;
  }

  .why-ceph {
    padding-top: 73px;
    padding-bottom: 60px;
  }
  
  .ceph-1 h2 {
    font-size: 25px;
  }

  .ceph-1 p {
    padding-top: 15px;
  }

  .ceph-lifecycle {
    padding-top: 73px;
    padding-bottom: 60px;
  }

  @media(min-width: 320px) and (max-width: 344px) {
    .ceph-lifecycle h1{
      font-size: 30px;
    }
  }
  @media(min-width: 345px) and (max-width: 360px) {
    .ceph-lifecycle h1{
      font-size: 34px;
    }
  }
  @media(min-width: 361px) and (max-width: 390px) {
    .ceph-lifecycle h1{
      font-size: 35px;
    }
  }

  @media(min-width: 576px) {
    .ceph-1 {
      margin-top: 75px;
    }
  }
</style>
