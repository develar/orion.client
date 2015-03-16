FROM develar/nginx
MAINTAINER Vladimir Krivosheev <develar@gmail.com>

# COPY lib/orion.client/bundles/*/web /data/
COPY lib/orion.client/bundles/org.eclipse.orion.client.users/web/ /data/
COPY lib/orion.client/bundles/org.eclipse.orion.client.webtools/web/ /data/
COPY lib/orion.client/bundles/org.eclipse.orion.client.git/web/ /data/
COPY lib/orion.client/bundles/org.eclipse.orion.client.help/web/ /data/
COPY lib/orion.client/bundles/org.eclipse.orion.client.ui/web/ /data/
COPY lib/orion.client/bundles/org.eclipse.orion.client.javascript/web/ /data/
COPY lib/orion.client/bundles/org.eclipse.orion.client.editor/web/ /data/
COPY lib/orion.client/bundles/org.eclipse.orion.client.core/web/ /data/

COPY lib/orionode.client /data/

EXPOSE 80

ENTRYPOINT ["nginx"]