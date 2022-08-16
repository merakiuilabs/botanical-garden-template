<template>
  <header class="relative">
    <div class="container px-6 py-6 mx-auto lg:flex lg:items-center lg:justify-between">
      <div class="flex items-center justify-between ">
        <a class="flex items-center -mx-1" href="#">
          <svg class="w-8 h-8 mx-1 sm:h-10 sm:w-10" viewBox="0 0 49 49" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M24.116 49C37.4348 49 48.2319 38.031 48.2319 24.5C48.2319 10.969 37.4348 0 24.116 0C10.7971 0 0 10.969 0 24.5C0 31.504 2.89291 37.8215 7.53104 42.2866C8.12815 41.9063 8.7211 41.5216 9.30948 41.1326C9.36842 40.7967 9.4391 40.3897 9.51815 39.9268C9.55946 39.6905 9.60387 39.4402 9.6559 39.179C9.69621 38.9688 9.74244 38.7526 9.79041 38.5283L9.81046 38.4345C10.0092 37.512 10.2176 36.4754 10.3882 35.389H10.3156C8.41217 35.4247 6.66631 34.9024 5.65798 33.749C5.19742 33.2236 4.87146 32.5661 4.77507 31.7779C4.67255 30.9354 4.83169 29.9421 5.3045 28.7934L5.3779 28.5804L5.69926 28.6519C6.92793 28.8944 8.50088 29.2177 9.57195 30.6292C10.0653 31.2779 10.4526 32.16 10.6454 33.3789C10.6633 33.1917 10.6793 33.0042 10.6933 32.8167C10.7762 31.711 10.7956 30.6075 10.7067 29.5693C8.63504 28.7398 6.97307 26.2773 6.49035 23.5906C6.30368 22.5507 6.28682 21.4765 6.4995 20.4707C6.82388 18.9365 7.65019 17.5577 9.05176 16.6313L9.19866 16.5255L9.42971 16.7229C11.2505 18.2323 12.164 20.3712 12.4118 22.6858C12.6459 24.887 12.2696 27.2467 11.4984 29.3732L11.3781 29.6908C11.5291 30.7021 11.5868 31.7757 11.5777 32.8555C11.5593 34.912 11.3115 36.9873 11.0009 38.6801C10.9535 38.9443 10.9014 39.1993 10.8448 39.4434C10.782 39.7092 10.7148 39.961 10.6459 40.1973L10.6316 40.2459C14.7321 37.4554 18.5897 34.4468 22.0602 31.2055C22.0508 31.0741 22.0361 30.8187 22.0331 30.4693C22.0315 30.3029 22.0316 30.1195 22.0469 29.9175C22.0618 29.7405 22.088 29.5526 22.1156 29.3551C22.1333 29.2282 22.1516 29.0974 22.1677 28.963C22.2279 28.473 22.2896 27.9462 22.3226 27.4117C21.0645 26.552 19.9959 25.3354 19.3003 24.0463C18.9606 23.4183 18.7096 22.7732 18.5628 22.1545C18.4052 21.4876 18.3531 20.8502 18.4357 20.2906C18.5933 19.2149 19.1458 18.3988 20.1893 18.133C20.9314 17.8455 21.7209 18.1253 22.4095 18.7938C23.1011 19.4653 23.6856 20.544 23.9962 21.783C24.4316 23.531 24.3003 25.5835 23.202 27.2651C23.2317 27.5264 23.2543 27.7884 23.271 28.0474C23.3 28.4796 23.3138 28.8993 23.3046 29.291C23.2975 29.5664 23.2891 29.8258 23.2586 30.0617C25.5089 27.8662 27.5801 25.5667 29.4294 23.1587C29.9268 22.5124 30.3353 21.9081 30.6982 21.2861L30.5366 20.973C29.6614 19.3268 29.1395 17.1755 29.1656 15.1547C29.1778 14.2453 29.3003 13.3623 29.542 12.5695C29.7914 11.7535 30.1555 11.0259 30.6513 10.4617C31.4271 9.57561 32.4844 9.05184 33.8523 9.14666C34.723 9.12801 35.3243 9.65181 35.6732 10.513C36.1674 11.7317 36.1183 13.6841 35.5966 15.5945C34.9527 17.9482 33.572 20.198 31.7152 21.0378C31.2708 21.9351 30.7656 22.7653 30.1011 23.6764C29.7506 24.1567 29.3917 24.6331 29.0247 25.1058C29.2302 25.0086 29.4436 24.9139 29.6635 24.8219C30.0145 24.6755 30.3805 24.538 30.757 24.4162C31.4576 23.0278 32.6907 21.7957 34.0642 20.9946C34.6961 20.6262 35.3571 20.3496 35.9982 20.1864C36.6745 20.0138 37.3294 19.9547 37.9093 20.0418C38.9865 20.2034 39.8234 20.7786 40.1111 21.8901C40.4125 22.6829 40.4079 23.3404 40.206 23.8782C39.8831 24.7441 39.014 25.3161 37.8863 25.6348C35.7029 26.2535 32.5386 25.9052 30.9733 25.257L30.9723 25.2565C30.9059 25.2895 30.8399 25.3229 30.7744 25.3566C30.0903 25.7088 29.4783 26.1243 28.9343 26.4937L28.9343 26.4937L28.9343 26.4937L28.9343 26.4938L28.9342 26.4938L28.9342 26.4938L28.9342 26.4938L28.9342 26.4938L28.9342 26.4938L28.9342 26.4938L28.9341 26.4938L28.9341 26.4938L28.9341 26.4939L28.9341 26.4939C28.7603 26.6119 28.5934 26.7252 28.4333 26.8302C28.1471 27.0185 27.8816 27.1721 27.6529 27.3044L27.6528 27.3045L27.6422 27.3106C27.2478 27.5371 26.9717 27.6797 26.8707 27.7308C24.3148 30.6854 21.445 33.4826 18.3425 36.1258C18.439 36.1119 18.5393 36.0987 18.6436 36.0869C18.8124 36.0679 18.9899 36.0507 19.1743 36.0327C19.8073 35.9711 20.5225 35.9014 21.2523 35.7293C21.4687 35.6779 21.6863 35.6211 21.9033 35.5574L21.987 35.372C22.9816 33.0947 24.7564 31.8122 26.7547 31.2324C27.5688 30.9977 28.4195 30.878 29.2641 30.864C30.5708 30.8438 31.8531 31.0661 32.964 31.3755L33.2684 31.4469L33.1323 31.8231C32.2065 34.5341 30.5218 35.8896 28.7041 36.4741C26.5136 37.1779 24.1071 36.7377 22.5258 36.1342C21.949 36.4308 21.3516 36.6668 20.7688 36.8547C20.293 37.0086 19.8324 37.1314 19.3979 37.2154C19.0658 37.2806 18.7522 37.3351 18.4645 37.3522C18.1662 37.3677 17.9014 37.3522 17.6765 37.332C17.3689 37.3036 17.1421 37.265 17.0113 37.239C14.3914 39.3898 11.6201 41.4355 8.74331 43.378C12.9167 46.8895 18.2737 49 24.116 49ZM11.0114 27.9892C11.5521 26.2913 11.8163 24.4779 11.6835 22.7543C11.5259 20.7024 10.8098 18.7795 9.31951 17.3447C8.2821 18.2215 7.74964 19.4075 7.54155 20.6713C7.39466 21.5574 7.40991 22.4853 7.56751 23.3932C7.93341 25.5055 9.03789 27.5171 10.5605 28.4423C10.4449 27.7963 10.2752 27.1887 10.0384 26.6376C9.98946 26.535 10.0323 26.4107 10.1333 26.3609C10.2358 26.3112 10.3583 26.3547 10.4072 26.4573C10.6511 26.9261 10.8507 27.4408 11.0114 27.9892ZM22.5488 24.6524C22.688 24.9504 22.8034 25.2783 22.8986 25.6249C23.3896 24.4456 23.4313 23.1334 23.2005 21.9664C22.9389 20.6435 22.3391 19.4948 21.6001 18.9321C21.2099 18.6352 20.786 18.5015 20.3622 18.6383C19.7808 18.9087 19.5145 19.4062 19.4289 20.0108C19.3523 20.5534 19.4548 21.1767 19.6614 21.8451C19.8251 22.3705 20.0608 22.9162 20.3545 23.4587C20.8522 24.3784 21.5208 25.2891 22.3316 26.0244C22.3079 25.5917 22.2543 25.1786 22.1524 24.8032C22.1126 24.6928 22.1677 24.5685 22.2764 24.5265C22.3865 24.4861 22.5075 24.5421 22.5488 24.6524ZM24.2238 34.9941C24.0152 35.1778 23.7965 35.3485 23.5703 35.5071C24.9526 35.9643 26.7796 36.2323 28.4914 35.7466C30.069 35.2974 31.5394 34.2014 32.4773 32.0298C31.293 31.8433 29.9481 31.82 28.6215 31.9942C27.7203 32.1123 26.8236 32.3174 25.9943 32.6921C24.9176 33.1785 23.9512 33.9275 23.2443 35.0524C23.4936 34.9332 23.737 34.7995 23.9714 34.6489C24.0647 34.579 24.1978 34.5993 24.2667 34.6941C24.3371 34.7889 24.3171 34.9226 24.2238 34.9941ZM32.451 24.636C33.9671 25.0596 36.1014 25.2538 37.6996 24.8871C39.1532 24.5513 40.1478 23.729 39.6138 22.0704C39.3292 21.4408 38.8151 21.147 38.1984 21.0522C37.6354 20.9652 36.9897 21.0755 36.3103 21.2994C35.7671 21.4766 35.2102 21.7346 34.6639 22.0548C33.7895 22.5663 32.9487 23.2386 32.3103 24.0291C32.7445 23.9552 33.1842 23.9113 33.6234 23.9063C33.7397 23.897 33.8422 23.984 33.8514 24.1021C33.8605 24.2203 33.7749 24.3244 33.6586 24.3337C33.2491 24.3997 32.8456 24.5043 32.451 24.636ZM33.1537 17.4958C32.915 18.1685 32.6929 18.7712 32.471 19.3278C33.5347 18.3933 34.3315 16.8876 34.8132 15.3568C35.3549 13.6375 35.5002 11.8669 35.0978 10.7399C34.8729 10.1135 34.4766 9.6969 33.8523 9.68291C32.9312 9.74975 32.2396 10.1352 31.7087 10.7042C31.1869 11.2638 30.8533 12.0224 30.6391 12.8836C30.4631 13.5924 30.3789 14.3681 30.3682 15.1702C30.3499 16.8413 30.6621 18.618 31.294 20.0621C31.3158 20.0536 31.3376 20.0449 31.3593 20.0359C31.7483 19.2256 32.1117 18.3337 32.5264 17.2564C32.5906 17.0792 32.7849 16.9906 32.9578 17.0558C33.1323 17.1227 33.2195 17.3201 33.1537 17.4958ZM5.92115 29.2597C5.69776 30.1784 5.69469 30.9525 5.82169 31.6085C5.93033 32.1681 6.15218 32.633 6.47962 33.0138C7.22631 33.8843 8.46259 34.3304 9.85651 34.4315C9.82897 32.8786 9.49543 31.8137 8.98285 31.0691C8.17496 29.8939 6.95091 29.5193 5.92115 29.2597Z" fill="#475F45" />
          </svg>
    
          <div class="mx-1 text-gray-700">
            <h3 class="uppercase tracking-[0.15em] font-medium ">Mist Gardens</h3>
            <p class="text-xs italic ">Museum & Botanical Garden</p>
          </div>
        </a>
  
        <button class="text-gray-600 lg:hidden " @click="isOpen = !isOpen">
          <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16m-7 6h7" />
          </svg>
        </button>
      </div>

      <div :class="[isOpen ? 'opacity-100 ' : 'opacity-0 -translate-x-full ']" class=" absolute lg:static transition-all duration-300 w-full py-12 lg:py-0 left-1/2 lg:opacity-100 lg:translate-x-0 lg:bg-transparent lg:w-auto -translate-x-1/2 top-20 sm:top-24 bg-[#475F45] ">
        <nav class="flex flex-col items-center space-y-8 lg:flex-row lg:space-y-0 lg:-mx-4">
            <a href="#" class="font-medium text-white lg:text-[#475F45] lg:hover:text-gray-400 lg:mx-4">
                Home
            </a>
  
            <a href="#" class="font-medium text-white lg:text-[#475F45] lg:hover:text-gray-400 lg:mx-4">
                Visit
            </a>
  
            <a href="#" class="font-medium text-white lg:text-[#475F45] lg:hover:text-gray-400 lg:mx-4">
                Exhibitions
            </a>
  
            <a href="#" class="font-medium text-white lg:text-[#475F45] lg:hover:text-gray-400 lg:mx-4">
                Programs & Events
            </a>
  
            <a href="#" class="font-medium text-white lg:text-[#475F45] lg:hover:text-gray-400 lg:mx-4">
                Store
            </a>
  
            <a class="px-8 py-2.5 text-white lg:text-[#475F45] lg:hover:bg-[#475F45] lg:hover:text-white duration-300 transition-colors font-medium lg:mx-4 border-2 lg:border-[#475F45] border-white" href="#">Membership</a>
        </nav>
      </div>
    </div>
  </header>

  <section class="container flex flex-col items-center px-6 py-12 mx-auto lg:flex-row">
      <div class="lg:w-1/2">
        <h1 class="max-w-xl font-serif text-4xl font-medium tracking-wide text-[#343D33] capitalize md:text-6xl ">A beatiful adventure awaits</h1>

        <p class="max-w-lg mt-4 text-gray-500">Lorem ipsum dolor sit amet consectetur adipisicing elit. At magnam voluptatibus perferendis odit optio.</p>
        
        <div class="mt-6 sm:flex sm:items-center">
          <a href="#" class="bg-[#475F45] hover:bg-[#475F45]/80 duration-300 transition-colors border-2 border-[#475F45] px-6 block text-center py-3 uppercase text-sm font-bold leading-4 tracking-widest text-white ">
            Buy Tickets
          </a>

          <a href="#" class="border-2 text-sm duration-300 transition-colors hover:bg-[#475F45] hover:text-white font-bold leading-4 mt-4 sm:mt-0 tracking-widest text-[#475F45] sm:mx-4 border-[#475F45] px-6 block text-center py-3 uppercase">
            Learn More
          </a>
        </div>
      </div>

      <div class="h-[38rem] mt-12 lg:mt-0 w-full mx-auto max-w-md overflow-hidden rounded-t-full outline outline-4 outline-offset-4 outline-[#475F45]/40">
        <img class="object-cover w-full h-full rounded-t-full " src="https://images.unsplash.com/photo-1531163859947-fa484f6eacd5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80" alt="main page" />
      </div>
  </section>

  <section class="bg-[#343D33] mt-12">
    <div class="container flex flex-col px-6 py-16 mx-auto mt-12">
      <div class="order-2 mt-8 lg:order-1 lg:mt-0 lg:flex lg:items-center lg:-mx-6">
        <img class="object-cover w-full lg:w-1/2 lg:mx-6 h-72 lg:h-96" src="https://images.unsplash.com/photo-1598901847919-b95dd0fabbb6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1374&q=80" alt="">
        
        <div class="mt-8 lg:w-1/2 lg:mx-6 lg:mt-0">
          <h3 class="font-serif text-2xl text-white capitalize md:text-4xl lg:text-5xl">
            Discover yourself with nature
          </h3>

          <p class="mt-4 text-gray-200 ">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam, nisi fugiat dicta impedit sed quisquam quas veritatis consectetur neque saepe, autem facilis dolore officiis minima explicabo perferendis ab porro magnam!
          </p>
          
          <a class="inline-flex px-6 py-3 mt-6 text-white border-2 border-white hover:bg-[#475F45] duration-300 transition-colors" href="#">
            Learn More
          </a>
        </div>
      </div>

        <img class="order-1 object-cover lg:order-2 w-ful h-72 lg:h-96 lg:mt-12" src="https://images.unsplash.com/photo-1610462275440-4ea0976f46f2?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1374&q=80" alt="">
    </div>
  </section>

  <section class="container px-6 py-12 mx-auto lg:py-16">
    <h3 class="font-serif text-3xl text-[#343D33] capitalize md:text-4xl lg:text-5xl">
      News & Updates
    </h3>
    
    <div class="mt-8 xl:-mx-6 xl:flex">
      <div class="xl:w-1/2 xl:mx-6">
        <img class="object-cover w-full h-96" src="https://images.unsplash.com/photo-1626838524909-7c584c2266f7?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80" alt="">

        <h2 class="mt-6 font-serif text-3xl font-medium text-gray-700">Plants Around Us</h2>

        <p class="mt-2 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tincidunt facilisis nuncLorem ipsum dolor sit.Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

        <p class="mt-4 italic text-gray-600">December 23, 2021</p>
      </div>

      <div class="mt-8 space-y-8 xl:w-1/2 xl:mx-6 xl:mt-0">
        <div class="md:-mx-4 md:flex md:items-center">
          <img class="object-cover w-full h-56 md:h-48 md:mx-4 md:w-80 shrink-0" src="https://images.unsplash.com/photo-1556426356-0fdc8b663467?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1498&q=80" alt="">

          <div class="mt-6 md:mx-4 md:mt-0">
            <h2 class="font-serif text-2xl font-medium text-gray-700 ">Lush Gardens</h2>
  
            <p class="mt-2 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tincidunt facilisis nuncLorem ipsum dolor sit...</p>
  
            <p class="mt-4 italic text-gray-600">December 16, 2021</p>
          </div>
        </div>

        <div class="md:-mx-4 md:flex md:items-center">
          <img class="object-cover w-full h-56 md:h-48 md:mx-4 md:w-80 shrink-0" src="https://images.unsplash.com/photo-1583470790878-4f4f3811a01f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1476&q=80" alt="">

          <div class="mt-6 md:mx-4 md:mt-0">
            <h2 class="font-serif text-2xl font-medium text-gray-700 ">Exotic Nature</h2>
  
            <p class="mt-2 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tincidunt facilisis nuncLorem ipsum dolor sit...</p>
  
            <p class="mt-4 italic text-gray-600">November 11, 2021</p>
          </div>
        </div>

        <div class="md:-mx-4 md:flex md:items-center">
          <img class="object-cover w-full h-56 md:h-48 md:mx-4 md:w-80 shrink-0" src="https://images.unsplash.com/photo-1638790491374-a2affccd8c8a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80" alt="">

          <div class="mt-6 md:mx-4 md:mt-0">
            <h2 class="font-serif text-2xl font-medium text-gray-700 ">It Starts with Soil</h2>
  
            <p class="mt-2 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tincidunt facilisis nuncLorem ipsum dolor sit...</p>
  
            <p class="mt-4 italic text-gray-600">November 3, 2021</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="bg-[#414840]">
    <div class="container px-6 py-8 mx-auto space-y-8 lg:space-y-0 lg:flex lg:justify-between">
      <div>
        <a class="flex items-center -mx-2" href="#">
          <svg class="w-10 h-10 mx-2" width="48" height="48" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" clip-rule="evenodd" d="M24 48C37.2548 48 48 37.2548 48 24C48 10.7452 37.2548 0 24 0C10.7452 0 0 10.7452 0 24C0 30.8612 2.87918 37.05 7.49526 41.424C8.08984 41.0512 8.68027 40.6742 9.26615 40.293C9.3248 39.9639 9.39513 39.5653 9.47378 39.1119C9.5149 38.8804 9.5591 38.6352 9.61087 38.3794C9.65099 38.1735 9.69699 37.9618 9.74472 37.742L9.76469 37.6501C9.96246 36.7464 10.1699 35.731 10.3397 34.6667H10.2671C8.37285 34.7017 6.63539 34.1901 5.6319 33.0602C5.17355 32.5455 4.84917 31.9014 4.75323 31.1294C4.65121 30.304 4.80959 29.331 5.28012 28.2057L5.35317 27.9971L5.67298 28.0671C6.89574 28.3047 8.46113 28.6214 9.52705 30.004C10.0181 30.6397 10.4037 31.5041 10.5955 32.6987C10.6133 32.515 10.6293 32.3309 10.6433 32.1469C10.7258 31.0637 10.7451 29.9828 10.6567 28.9657C8.59508 28.153 6.94127 25.7409 6.4609 23.1092C6.27513 22.0905 6.25835 21.0382 6.47001 20.053C6.79283 18.55 7.61516 17.1994 9.01 16.2919L9.15619 16.1882L9.38613 16.3816C11.1982 17.8602 12.1072 19.9555 12.3539 22.2229C12.5869 24.3791 12.2123 26.6906 11.4449 28.7737L11.3249 29.0855C11.4751 30.076 11.5325 31.1274 11.5234 32.1849C11.5051 34.1995 11.2585 36.2324 10.9494 37.8906C10.9022 38.1495 10.8504 38.3993 10.794 38.6384C10.7316 38.8987 10.6647 39.1454 10.5961 39.3769L10.5819 39.4243C14.6626 36.6908 18.5016 33.7437 21.9554 30.5686C21.946 30.4399 21.9314 30.1898 21.9284 29.8475C21.9269 29.6846 21.9269 29.5049 21.9421 29.3069C21.957 29.1336 21.9831 28.9495 22.0105 28.7561C22.0281 28.6318 22.0463 28.5036 22.0624 28.372C22.1223 27.8919 22.1836 27.3759 22.2165 26.8523C20.9644 26.0101 19.901 24.8183 19.2086 23.5555C18.8706 22.9403 18.6209 22.3084 18.4747 21.7023C18.3178 21.0491 18.2661 20.4247 18.3483 19.8765C18.5051 18.8228 19.0549 18.0233 20.0934 17.7629C20.832 17.4812 21.6177 17.7554 22.3029 18.4102C22.9912 19.068 23.5729 20.1248 23.882 21.3384C24.3153 23.0507 24.1847 25.0613 23.0917 26.7086C23.1213 26.9646 23.1438 27.2213 23.1603 27.4751C23.1893 27.8984 23.2029 28.3095 23.1938 28.6933C23.1867 28.963 23.1784 29.2171 23.148 29.4481C25.3876 27.2974 27.4489 25.0448 29.2893 22.6859C29.7847 22.0523 30.1914 21.46 30.5528 20.8502L30.3927 20.545C29.5217 18.9324 29.0024 16.825 29.0283 14.8454C29.0405 13.9546 29.1623 13.0896 29.4029 12.313C29.6511 11.5136 30.0135 10.8009 30.5069 10.2482C31.2789 9.38021 32.3312 8.86713 33.6925 8.96001C34.559 8.94174 35.1574 9.45486 35.5046 10.2985C35.9964 11.4923 35.9476 13.4048 35.4284 15.2763C34.7874 17.5828 33.4125 19.7875 31.5636 20.6094C31.1214 21.488 30.6188 22.3009 29.9579 23.1929C29.6088 23.6637 29.2514 24.1308 28.8858 24.5941C29.0908 24.4987 29.3037 24.4057 29.5231 24.3153C29.8722 24.172 30.2361 24.0374 30.6104 23.9182C31.3077 22.558 32.5349 21.3509 33.9019 20.5661C34.5308 20.2053 35.1886 19.9343 35.8266 19.7744C36.4996 19.6054 37.1514 19.5475 37.7285 19.6327C38.8005 19.7911 39.6334 20.3546 39.9197 21.4433C40.2197 22.2199 40.2151 22.864 40.0141 23.3909C39.6928 24.2391 38.8279 24.7994 37.7057 25.1116C35.5327 25.7177 32.3837 25.3765 30.8259 24.7415L30.8253 24.7412C30.7593 24.7735 30.6937 24.8061 30.6286 24.8391C29.9478 25.1841 29.3387 25.5912 28.7974 25.953C28.6243 26.0687 28.4582 26.1797 28.2989 26.2826C28.014 26.467 27.7498 26.6175 27.5223 26.7471L27.5223 26.7471L27.5222 26.7472L27.5116 26.7532C27.1168 26.9764 26.8411 27.1164 26.742 27.1657C24.1986 30.0597 21.3428 32.7996 18.2555 35.3886C18.3518 35.3749 18.4521 35.3619 18.5563 35.3503C18.7243 35.3317 18.9009 35.3148 19.0844 35.2972C19.7144 35.2368 20.4261 35.1686 21.1525 35C21.3675 34.9498 21.5837 34.8942 21.7994 34.8319L21.8827 34.6502C22.8725 32.4193 24.6388 31.163 26.6275 30.595C27.4376 30.3651 28.2843 30.2479 29.1248 30.2342C30.4252 30.2144 31.7013 30.4322 32.8069 30.7352L33.1098 30.8052L32.9743 31.1737C32.0531 33.8294 30.3765 35.1572 28.5674 35.7298C26.3876 36.4192 23.9929 35.9881 22.4192 35.3969C21.8453 35.6873 21.251 35.9184 20.6713 36.1024C20.1978 36.2532 19.7394 36.3735 19.3069 36.4557C18.9765 36.5197 18.6644 36.573 18.3781 36.5897C18.0812 36.605 17.8177 36.5897 17.5939 36.5699C17.2871 36.5421 17.0611 36.5042 16.9311 36.4787C14.3234 38.5859 11.5651 40.5901 8.70176 42.4931C12.855 45.9327 18.1861 48 24 48ZM10.9601 27.4186C11.4983 25.7551 11.7613 23.9786 11.6291 22.2899C11.4722 20.2799 10.7596 18.3963 9.27646 16.9908C8.24404 17.8496 7.71414 19.0115 7.50705 20.2495C7.36086 21.1174 7.37604 22.0265 7.53289 22.9158C7.897 24.9848 8.996 26.9552 10.5111 27.8616C10.3961 27.2289 10.2271 26.6338 9.99156 26.0939C9.94283 25.9934 9.98548 25.8716 10.086 25.8229C10.188 25.7742 10.3099 25.8168 10.3586 25.9173C10.6014 26.3768 10.8 26.8811 10.9601 27.4186ZM22.4416 24.1494C22.5801 24.4412 22.695 24.7624 22.7897 25.1018C23.2784 23.9467 23.3198 22.6613 23.0901 21.518C22.8297 20.2222 22.2329 19.0969 21.4974 18.5457C21.1091 18.2548 20.6873 18.1239 20.2655 18.2579C19.6868 18.5228 19.4219 19.0101 19.3366 19.6024C19.2605 20.1339 19.3625 20.7445 19.568 21.3993C19.731 21.9139 19.9655 22.4485 20.2579 22.9799C20.7532 23.8808 21.4185 24.773 22.2255 25.4933C22.2019 25.0695 22.1485 24.6648 22.0472 24.2971C22.0076 24.1889 22.0624 24.0672 22.1705 24.026C22.2801 23.9865 22.4005 24.0413 22.4416 24.1494ZM24.1097 34.2798C23.9019 34.4599 23.6841 34.6272 23.4588 34.7826C24.8344 35.2304 26.6524 35.4928 28.3558 35.0172C29.9258 34.5771 31.3891 33.5035 32.3225 31.3762C31.1439 31.1935 29.8055 31.1707 28.4853 31.3413C27.5884 31.457 26.696 31.658 25.8707 32.0249C24.7991 32.5015 23.8372 33.2353 23.1337 34.3375C23.3823 34.2205 23.6248 34.0894 23.8585 33.9417C23.9513 33.8731 24.0838 33.893 24.1523 33.9859C24.2224 34.0788 24.2026 34.2097 24.1097 34.2798ZM32.2969 24.1333C33.8057 24.5482 35.9294 24.7384 37.5199 24.3791C38.9665 24.0502 39.9562 23.2447 39.4248 21.6199C39.1416 21.0032 38.6299 20.7154 38.0163 20.6226C37.4559 20.5373 36.8133 20.6454 36.1372 20.8647C35.5966 21.0383 35.0424 21.291 34.4987 21.6047C33.6285 22.1058 32.7917 22.7644 32.1563 23.5388C32.5888 23.4664 33.0266 23.4233 33.464 23.4184C33.5797 23.4093 33.6817 23.4945 33.6908 23.6102C33.7 23.726 33.6147 23.828 33.499 23.8371C33.0913 23.9018 32.6896 24.0043 32.2969 24.1333ZM32.9957 17.1385C32.7578 17.7985 32.5365 18.3895 32.3154 18.9355C33.3752 18.0202 34.169 16.5441 34.6488 15.0434C35.1878 13.3592 35.3325 11.6248 34.932 10.5208C34.7081 9.9071 34.3138 9.49902 33.6925 9.48532C32.7758 9.55079 32.0875 9.92841 31.5591 10.4857C31.0399 11.0339 30.7079 11.7771 30.4947 12.6207C30.3196 13.3151 30.2358 14.0749 30.2252 14.8606C30.2069 16.4976 30.5176 18.2381 31.1465 19.6527C31.1675 19.6446 31.1885 19.6363 31.2094 19.6278C31.5967 18.8338 31.9586 17.9598 32.3715 16.904C32.4354 16.7304 32.6288 16.6436 32.8008 16.7075C32.9744 16.773 33.0612 16.9664 32.9957 17.1385ZM5.89381 28.6625C5.67148 29.5625 5.66844 30.3208 5.79482 30.9634C5.90294 31.5116 6.12372 31.9669 6.44959 32.34C7.19269 33.1928 8.42302 33.6298 9.81024 33.7287C9.78284 32.2075 9.4509 31.1644 8.94078 30.435C8.13677 29.2838 6.91861 28.9168 5.89381 28.6625Z" fill="white" />
          </svg>

          <div class="mx-2 text-white">
            <h3 class="font-medium tracking-widest uppercase">Mist Gardens</h3>
            <p class="mt-1 text-xs italic leading-3 tracking-wide capitalize">museum & botanical garden</p>
          </div>
        </a>

        <p class="max-w-lg mt-6 leading-relaxed text-white ">
         Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt voluptatum amet molestiae consequatur quam velit sint modi aut illo dolorem.
        </p>
      </div>

      <div class="flex flex-col space-y-4">
        <a href="#" class="text-white hover:text-gray-300">Home</a>
        <a href="#" class="text-white hover:text-gray-300">Visit</a>
        <a href="#" class="text-white hover:text-gray-300">Exhibitions</a>
        <a href="#" class="text-white hover:text-gray-300">Programs & Events</a>
        <a href="#" class="text-white hover:text-gray-300">Store</a>
        <a href="#" class="text-white hover:text-gray-300">Membership</a>
      </div>
      
      <div>
        <p class="font-medium text-white capitalize">Connect</p>

        <div class="flex mt-6 -mx-4">
          <a class="mx-4 text-white hover:text-gray-300" href="#">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M23 3.00005C22.0424 3.67552 20.9821 4.19216 19.86 4.53005C19.2577 3.83756 18.4573 3.34674 17.567 3.12397C16.6767 2.90121 15.7395 2.95724 14.8821 3.2845C14.0247 3.61176 13.2884 4.19445 12.773 4.95376C12.2575 5.71308 11.9877 6.61238 12 7.53005V8.53005C10.2426 8.57561 8.50127 8.18586 6.93101 7.39549C5.36074 6.60513 4.01032 5.43868 3 4.00005C3 4.00005 -1 13 8 17C5.94053 18.398 3.48716 19.099 1 19C10 24 21 19 21 7.50005C20.9991 7.2215 20.9723 6.94364 20.92 6.67005C21.9406 5.66354 22.6608 4.39276 23 3.00005V3.00005Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
            </svg>
          </a>

          <a class="mx-4 text-white hover:text-gray-300" href="#">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M18 2H15C13.6739 2 12.4021 2.52678 11.4645 3.46447C10.5268 4.40215 10 5.67392 10 7V10H7V14H10V22H14V14H17L18 10H14V7C14 6.73478 14.1054 6.48043 14.2929 6.29289C14.4804 6.10536 14.7348 6 15 6H18V2Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
            </svg>
          </a>

          <a class="mx-4 text-white hover:text-gray-300" href="#">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M16 8C17.5913 8 19.1174 8.63214 20.2426 9.75736C21.3679 10.8826 22 12.4087 22 14V21H18V14C18 13.4696 17.7893 12.9609 17.4142 12.5858C17.0391 12.2107 16.5304 12 16 12C15.4696 12 14.9609 12.2107 14.5858 12.5858C14.2107 12.9609 14 13.4696 14 14V21H10V14C10 12.4087 10.6321 10.8826 11.7574 9.75736C12.8826 8.63214 14.4087 8 16 8V8Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
              <path d="M6 9H2V21H6V9Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
              <path d="M4 6C5.10457 6 6 5.10457 6 4C6 2.89543 5.10457 2 4 2C2.89543 2 2 2.89543 2 4C2 5.10457 2.89543 6 4 6Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
            </svg>
          </a>
          
          <a class="mx-4 text-white hover:text-gray-300" href="#">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 4H20C21.1 4 22 4.9 22 6V18C22 19.1 21.1 20 20 20H4C2.9 20 2 19.1 2 18V6C2 4.9 2.9 4 4 4Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
              <path d="M22 6L12 13L2 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
            </svg>
          </a>
        </div>
      </div>
    </div>
    
    <p class="w-full py-6 mx-auto text-white text-center bg-[#343D33]">
      &copy; 2022 Mist Gardens. All rights reserved.
    </p>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      isOpen: false
    }
  }
}
</script>
