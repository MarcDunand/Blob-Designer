# Blob-Designer

An approach to creating a wide variety of blob types. My challenge was to create an entirely novel algorithm for designing blobs. I use a set of Truchet tiles that have a randomwalk algorithm intersecting the borders of the tiles. I then link together all intersections along the borders of a single tile using a recursive algorithm that guarantees non-intersection. I then convert these linked lines into curves to avoid corners - in doing so reintroducing some overlap. 

This is a p5.js project. To see it in action. See my website, www.marcdunand.com or directly at https://openprocessing.org/sketch/2326546
