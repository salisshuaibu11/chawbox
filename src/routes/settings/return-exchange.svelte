<script>
	import RecentlyViewed from '../../components/Products.svelte';
	import AccountSideNav from '../../components/AccountSideNav.svelte';
</script>

<section class="w-screen -mt-24">
	<div class="bg-green-50 relative w-screen min-h-[250px] px-4 py-8">
		<div>
			<a href="#">Home </a>/
			<a href="#">Account </a> /
			<a href="#">Returns & Exchanges </a>
		</div>
		<div class="flex justify-center items-center mt-12">
			<img class="absolute mx-auto" src="/icons/return-exchange.svg" alt="" />
		</div>
	</div>

	<div class="w-full md:flex md:px-18 lg:px-24 xl:px-32">
		<AccountSideNav />
		<section class="flex-1 mx-4 md:mx-12 my-5 h-fit">
			<h5 class="font-bold text-2xl my-4">Returns & Exchanges</h5>

			<p class="text-gray-600 font-normal text-lg">
				All rights reserved. The gohenry card is issued by IDT Financial Services Limited, a
				principal member of Visa Europe. IDT Financial Services Limited is a regulated bank,
				licensed by the Financial Services Commission, Gibraltar. Registered office: 57-63 Line Wall
				Road, Gibraltar. Registered No. 95716. All rights reserved. The gohenry card is issued by
				IDT Financial Services Limited, a principal member of Visa Europe. IDT Financial Services
				Limited is a regulated bank, licensed by the Financial Services Commission, Gibraltar.
				Registered office: 57-63 Line Wall Road, Gibraltar. Registered No. 95716.
				<br /><br />
				Have you ever thought of what to do with those people who actually think they are also your friends;
				your colleagues at work, in school, the neighbour you laugh with all the time. You are throwing
				a private party and you did not bother to send out invitations because you have a small group
				of friends whom you planned to celebrate with. They all trooped into the mini flat where you
				live with your little brother, Jed. Some cramped together on the two-set of sofa and others leaning
				against the wall because there is no other place to sit. You don’t like the noise emanating from
				the loud voices of everyone trying to wish you congratulations at the same time on your recent
				promotion at work. You are even pissed at the security guard from three compounds away who is
				insisting that you give him a few bucks of cash to wash the celebration for him. You wonder why
				he is at your party, meant for your close friends when he should be at his duty post. You said
				okay, no problem, that you would see him about that later.
				<br /><br />
				Have you ever thought of what to do with those people who actually think they are also your friends;
				your colleagues at work, in school, the neighbour you laugh with all the time. You are throwing
				a private party and you did not bother to send out invitations because you have a small group
				of friends whom you planned to celebrate with. They all trooped into the mini flat where you
				live with your little brother, Jed. Some cramped together on the two-set of sofa and others leaning
				against the wall because there is no other place to sit. You don’t like the noise emanating from
				the loud voices of everyone trying to wish you congratulations at the same time on your recent
				promotion at work. You are even pissed at the security guard from three compounds away who is
				insisting that you give him a few bucks of cash to wash the celebration for him. You wonder why
				he is at your party, meant for your close friends when he should be at his duty post. You said
				okay, no problem, that you would see him about that later.
			</p>
		</section>
	</div>
</section>

<RecentlyViewed title="Recently Viewed" subTitle="Recently Viewed Items" />
