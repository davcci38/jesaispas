---
title: "test"
order: 5
in_menu: true
---
<h1>carousel</h1>
<h1 class=test>
<html/>
- let sides = '<div class="side"></div><div class="side"></div><div class="side"></div><div class="side"></div><div class="side"></div><div class="side"></div>';
.scene
	.content
		.water.one
		.water.two
		.water.three
		.water.four
		.water.five
		.water.six
		.water.fall
		.water.foam
			div
			div
		
		.cuboid.brick-1 !{sides}
		.cuboid.brick-2 !{sides}
		.cuboid.brick-3 !{sides}
		.cuboid.brick-4 !{sides}
		.cuboid.brick-5 !{sides}
		.cuboid.brick-6 !{sides}
		.cuboid.brick-7 !{sides}
		.cuboid.brick-8 !{sides}
		.cuboid.brick-9 !{sides}
		.cuboid.brick-10 !{sides}
		.cuboid.brick-11 !{sides}
		.cuboid.brick-12 !{sides}
		.cuboid.brick-13 !{sides}
		.cuboid.brick-14 !{sides}
		.cuboid.brick-15 !{sides}
		
		.cuboid.col-1 !{sides}
		.cuboid.col-2 !{sides}
		.cuboid.col-3 !{sides}
		.cuboid.col-4 !{sides}
		
		.cuboid.tower-1 !{sides}
		.cuboid.tower-2 !{sides}
		.cuboid.tower-3 !{sides}
		.cuboid.tower-4 !{sides}
		.cuboid.tower-5 !{sides}
		.cuboid.tower-6 !{sides}
		.cuboid.tower-7 !{sides}
		.cuboid.tower-8 !{sides}
		
		.cuboid.roof-1 !{sides}
		.cuboid.roof-2 !{sides}
			
		.shape.one
			- for (var c=0; c<4; c++)
				.cuboid !{sides}
		.shape.two
			- for (var c=0; c<4; c++)
				.cuboid !{sides}
				
		.fence
			- for (var s=0; s<4; s++)
				.side
		
		.wheel
			- for (var c=0; c<8; c++)
				.cuboid !{sides}
			.cuboid.axis !{sides}
		.cuboid.wheel-door !{sides}

		.cuboid.house !{sides}
		.cuboid.house-roof !{sides}
		.cuboid.house-step !{sides}
		.cuboid.house-step.two !{sides}
		.cuboid.house-step.three !{sides}
		.cuboid.house-door.one !{sides}
		.cuboid.house-door.two !{sides}
		.cuboid.house-window !{sides}
		.cuboid.house-window.two !{sides}
		.cuboid.house-window.three !{sides}
		.cuboid.house-pulley !{sides}
		.cuboid.house-chimney !{sides}
		.cuboid.house-chimney.base !{sides}
		.cuboid.flour-sack !{sides}
		.cuboid.flour-sack.two !{sides}
		.cuboid.flour-sack.three !{sides}
		.cuboid.flour-sack.four !{sides}
		.cuboid.flour-sack.five !{sides}

		.trails
		.cuboid.ground !{sides}
		
		.cuboid.seat !{sides}
		.cuboid.seat.back !{sides}
		
		.cuboid.sculpture.base !{sides}
		.cuboid.sculpture.one.metal !{sides}
		.cuboid.sculpture.two.metal !{sides}
		.cuboid.sculpture.three.metal !{sides}
		.cuboid.sculpture.four.metal !{sides}
		
		.flowers
			- for (var d=0; d<15; d++)
				div
					span
		
		.vegetables
			- for (var d=0; d<4; d++)
				div 