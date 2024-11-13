next js api routes

import { NextResponse } from "next/server.js";

export async function GET(req) {
//get search params
// const searchParams = await req.nextUrl.searchParams
// const name = searchParams.get('name');
return NextResponse.json({ name: "jibon roy" });
}
export async function POST(req) {
//get action form data
// cosnt data = req.json();
// const bodyData = await req.formData()
return NextResponse.json({ name: "jibon roy" });
}
export async function PUT(req) {
// get params id
// cosnt data = req.json();
//const id = await req.params;
return NextResponse.json({ name: "jibon roy" });
}
export async function PATCH(req, { params }) {
// get params id
// const id = await params.id;
return NextResponse.json({ name: "jibon roy" });
}
export async function DELETE(req, { params }) {
// get params id
// const id = await params.id;
return NextResponse.json({ name: "jibon roy" });
}
