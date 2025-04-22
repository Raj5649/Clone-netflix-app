import React from "react";

export default function NetflixClone() {
  return (
    <div className="bg-black text-white min-h-screen">
      {/* Header */}
      <div className="relative">
        <img
          src="https://i.ibb.co/BZ8CjRh/joker-fire.jpg"
          alt="Joker Poster"
          className="w-full h-[80vh] object-cover opacity-60"
        />
        <div className="absolute top-0 left-0 w-full h-full flex flex-col justify-center pl-10 pr-10 bg-black bg-opacity-50">
          <h1 className="text-5xl font-bold mb-4">Watch Joker Now</h1>
          <p className="text-lg max-w-xl mb-6">
            Forever alone in a crowd, failed comedian Arthur Fleck seeks connection as he
            walks the streets of Gotham City. Arthur wears two masks -- the one he
            paints for his day job as a clown, and the guise he projects in a futile
            attempt to feel like he's part of the world around him.
          </p>
          <button className="bg-white text-black px-6 py-2 font-semibold rounded hover:bg-gray-300 w-fit">
            Play
          </button>
        </div>
      </div>

      {/* Section: Documentaries */}
      <div className="px-10 py-6">
        <h2 className="text-2xl font-semibold mb-4">Documentaries</h2>
        <div className="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-4">
          <img src="https://i.ibb.co/Fz2zMRC/doc1.jpg" alt="Doc 1" className="rounded" />
          <img src="https://i.ibb.co/vvWzrmx/doc2.jpg" alt="Doc 2" className="rounded" />
          <img src="https://i.ibb.co/0FbGtJ9/doc3.jpg" alt="Doc 3" className="rounded" />
          <img src="https://i.ibb.co/bKmkQK9/doc4.jpg" alt="Doc 4" className="rounded" />
          <img src="https://i.ibb.co/nP8DN7X/doc5.jpg" alt="Doc 5" className="rounded" />
        </div>
      </div>
    </div>
  );
}
