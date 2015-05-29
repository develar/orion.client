FROM develar/nginx
MAINTAINER Vladimir Krivosheev <develar@gmail.com>

COPY lib/orion.client/bundles/org.eclipse.orion.client.ui/web/ /data/
COPY lib/orion.client/bundles/org.eclipse.orion.client.editor/web/ /data/
COPY lib/orion.client/bundles/org.eclipse.orion.client.core/web/ /data/

EXPOSE 80

ENTRYPOINT ["nginx"]